<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <meta charset="utf-8">
    <meta http-equiv='X-UA-Compatible' content='IE=edge' />
    <title>Hello World</title>
    <script id='sap-ui-bootstrap'
        src='https://openui5.hana.ondemand.com/1.28.15/resources/sap-ui-core.js'
        data-sap-ui-theme='sap_bluecrystal'
        data-sap-ui-libs='sap.ui.commons'></script>
</head>
<body>
    <div id='content'>
        <script>
            var btn = new sap.ui.commons.Button({
            text:'Нажмите на кнопку!',
            press: function() 
                {
                alert("Нажмите OK")
                }
    });
    btn.placeAt('content');
    </script></div>
</body>
</html>
