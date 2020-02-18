## Mã nhúng trong popup đặt phòng

Sau khi đặt phòng xong qua popup, nếu bạn muốn gửi thông báo xác nhận đặt phòng thành công cho user, trước tiên hãy nhúng đoạn mã sau vào cuối thẻ body trong trang đặt phòng của bạn

### Bản Dev
```HTML
<script language="javascript" type="text/javascript">
        var message;
        message = {
            "text":"Message trả về cho user khi đặt phòng thành công"
          
        };

        var signed_request;
        window.extAsyncInit = function() {
           //con chính
            MessengerExtensions.getContext('115279665149396',
                function success(thread_context){
                    // signed_request
                    signed_request = thread_context.signed_request;
                    console.log('signed_request ', signed_request)
                },
                function error(err){
                    // error
                }
            );
        };

        var bizfly = {
            init: function() {
                return !0
            },
            confirm: function(message) {
                var data = new FormData();
                data.append('message', JSON.stringify(message));
                data.append('signed_request', signed_request);
                
                var baseUrl = "https://chat.todo.vn"; //con dev
                var xhr = new XMLHttpRequest();
                xhr.open('POST', baseUrl + "/api/facebook/sendCompleteScriptWow", true);
                xhr.onload = function () {
                    if (200 === xhr.status)
                    {
                        var e = JSON.parse(xhr.responseText);
                        MessengerExtensions.requestCloseBrowser(function success() {
                            // webview closed
                        }, function error(err) {
                            // an error occurred
                        });
                    }
                    else
                    {
                        console.log("Lỗi " + xhr.status)
                    }

                };
                xhr.send(data);
            },
            get_crm_id: function(){
               var data = new FormData();
                data.append('signed_request', signed_request);
                
                var baseUrl = "https://chat.bizfly.vn"; //con chính
                var xhr = new XMLHttpRequest();
                xhr.open('POST', baseUrl + "/api/facebook/getCrmId", true);
                xhr.onload = function () {
                    if (200 === xhr.status)
                    {
                        var result = JSON.parse(xhr.responseText);
                        return result;
                    }
                    else
                    {
                        console.log("Lỗi " + xhr.status)
                    }

                };
                xhr.send(data);
            }
        };
        (function(d, s, id){
            var js, fjs = d.getElementsByTagName(s)[0];
            if (d.getElementById(id)) {return;}
            js = d.createElement(s); js.id = id;
            js.src = "//connect.facebook.net/en_US/messenger.Extensions.js";
            fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'Messenger'));
    </script>
```
### Bản Chính
```HTML
<script language="javascript" type="text/javascript">
        var message;
        message = {
            "text":"Message trả về cho user khi đặt phòng thành công"
          
        };

        var signed_request;
        window.extAsyncInit = function() {
           //con chính
            MessengerExtensions.getContext('1824967184492332',
                function success(thread_context){
                    // signed_request
                    signed_request = thread_context.signed_request;
                    console.log('signed_request ', signed_request)
                },
                function error(err){
                    // error
                }
            );
        };

        var bizfly = {
            init: function() {
                return !0
            },
            confirm: function(message) {
                var data = new FormData();
                data.append('message', JSON.stringify(message));
                data.append('signed_request', signed_request);
                
                var baseUrl = "https://chat.bizfly.vn"; //con chính
                var xhr = new XMLHttpRequest();
                xhr.open('POST', baseUrl + "/api/facebook/sendCompleteScriptWow", true);
                xhr.onload = function () {
                    if (200 === xhr.status)
                    {
                        var e = JSON.parse(xhr.responseText);
                        MessengerExtensions.requestCloseBrowser(function success() {
                            // webview closed
                        }, function error(err) {
                            // an error occurred
                        });
                    }
                    else
                    {
                        console.log("Lỗi " + xhr.status)
                    }

                };
                xhr.send(data);
            },
            get_crm_id: function(){
               var data = new FormData();
                data.append('signed_request', signed_request);
                
                var baseUrl = "https://chat.bizfly.vn"; //con chính
                var xhr = new XMLHttpRequest();
                xhr.open('POST', baseUrl + "/api/facebook/getCrmId", true);
                xhr.onload = function () {
                    if (200 === xhr.status)
                    {
                        var result = JSON.parse(xhr.responseText);
                        return result;
                    }
                    else
                    {
                        console.log("Lỗi " + xhr.status)
                    }

                };
                xhr.send(data);
            }
        };
        (function(d, s, id){
            var js, fjs = d.getElementsByTagName(s)[0];
            if (d.getElementById(id)) {return;}
            js = d.createElement(s); js.id = id;
            js.src = "//connect.facebook.net/en_US/messenger.Extensions.js";
            fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'Messenger'));
    </script>
```



!> Khi đặt phòng thành công, hãy gọi tới hàm bizfly.confirm(your_message) để gửi thông báo đặt phòng thành công cho user
