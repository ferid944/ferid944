/* Ümumi üslublar */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4; /* Açıq boz fon */
    color: #333; /* Tünd boz mətn */
    margin: 0;
    padding: 0;
}

/* Başlıq üslubu */
h1 {
    text-align: center;
    color: #4CAF50; /* Yaşıl rəngdə başlıq */
    margin-top: 50px;
}

/* Kontent qutusu */
.container {
    width: 80%;
    margin: 20px auto;
    background-color: #ffffff; /* Ağ fon */
    border-radius: 10px; /* Künclərin yuvarlaq olması */
    padding: 20px;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1); /* Yumşaq kölgə */
}

/* Formalar */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
}

input[type="text"],
input[type="password"],
input[type="email"] {
    width: 100%;
    max-width: 400px;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    font-size: 18px;
    cursor: pointer;
    width: 200px;
    margin-top: 20px;
}

input[type="submit"]:hover {
    background-color: #45a049; /* Hover effekti */
}

/* Giriş/Qeydiyyat formu */
.login-register-container {
    display: flex;
    justify-content: space-around;
    gap: 50px;
    margin-top: 50px;
}

/* Bağlantılar */
a {
    color: #4CAF50;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Responsivlik */
@media (max-width: 768px) {
    .container {
        width: 90%;
    }

    .login-register-container {
        flex-direction: column;
        align-items: center;
    }

    input[type="submit"] {
        width: 100%;
    }
}
