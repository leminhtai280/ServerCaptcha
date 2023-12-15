# ServerCaptcha
//createTask
POST [http://103.77.214.181:7777/create]
{
    "sitekey": "SITE KEY",
    "blob": "BLOB" # tùy loại captcha cần data blob
}
==> Example response:
* {"taskId":{idTask}}
* {"taskId":1}




//getTaskResult
GET [http://103.77.214.181:7777/result/{idTask}
==> Example response:
* {"result":"Processing"}
* {"result":"90117a10a6f6d4998.5896890504|r=ap-southeast-1|meta=3|meta_width=558|meta_height=523|metabgclr=transparent|metaiconclr=%23555555|guitextcolor=%23000000|pk=2CB16598-CB82-4CF7-B332-5990DB66F3AB|at=40|ag=101|cdn_url=https%3A%2F%2Fclient-api.arkoselabs.com%2Fcdn%2Ffc|lurl=https%3A%2F%2Faudio-ap-southeast-1.arkoselabs.com|surl=https%3A%2F%2Fclient-api.arkoselabs.com|smurl=https%3A%2F%2Fclient-api.arkoselabs.com%2Fcdn%2Ffc%2Fassets%2Fstyle-manager"}
