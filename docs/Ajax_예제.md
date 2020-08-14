# Ajax 예제

```javascript
$.ajax({
    method: 'GET',
    url: '/sms/sms.php',
    data: {"sms_number": $('#phone').val()},
    success:function(data){
    alert('전송되었습니다.'+data);
    //location.replace('/sms/sms.php');
    },
    error:function(){
    alert('ajax error.');
    }
});
```

