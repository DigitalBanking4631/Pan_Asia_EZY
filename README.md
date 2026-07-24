<style>
body{
    margin:0;
    font-family:Arial,Helvetica,sans-serif;
    background:#f5f7fa;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    background:#fff;
    width:420px;
    max-width:90%;
    padding:40px;
    border-radius:12px;
    box-shadow:0 10px 30px rgba(0,0,0,.15);
    text-align:center;
}

img{
    width:120px;
    margin-bottom:20px;
}

h1{
    color:#004b8d;
    margin-bottom:15px;
}

p{
    color:#555;
    font-size:16px;
}

.loader{
    margin:25px auto;
    width:45px;
    height:45px;
    border:5px solid #ddd;
    border-top:5px solid #004b8d;
    border-radius:50%;
    animation:spin 1s linear infinite;
}

@keyframes spin{
    100%{
        transform:rotate(360deg);
    }
}
</style>
