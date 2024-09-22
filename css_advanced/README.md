section h2 {
    text-align: center;
    font-size: 28px;
    margin-bottom: 30px;
    color: #6c63ff;
}

section div {
    display: inline-block;
    width: 20%;
    margin: 0 1.5%;
    text-align: center;
    background-color: #15058e;
    padding: 20px;
    border-radius: 10px;
   
}

section div img {
    width: 50px;
    margin-bottom: 20px;
}

section div h3 {
    font-size: 19px;
    margin-bottom: 10px;
    color: #ffffff;
}

section div p {
    font-size: 16px;
    color: #ffffff;
}


section button {
    display: block;
    margin: 30px auto;
    padding: 12px 30px;
    background-color: #6c63ff;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s;
}

section button:hover {
    background-color: #5547d0;
}


section div div {
    margin-bottom: 30px;
}

section div div h3 {
    font-size: 13px;
    margin-bottom: 20px;
    cursor: pointer;
    color: #ffffff;
}

section div div p {
    font-size: 14px;
    color: #ffffff;
    margin-bottom: 10px;
}


footer {
    background-color: #ffffff;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer section div {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 60px;
}

footer section div img {
    width: 80px;
    margin-right: 20px;
}

footer section div i {
    font-size: 24px;
    margin: 0 10px;
    color: #fff;
    transition: color 0.3s;
}

footer section div i:hover {
    color: #6c63ff;
}

footer p {
    font-size: 14px;
    color: #bbb;
}


@media (max-width: 768px) {
    section div {
        width: 45%;
        margin-bottom: 20px;
    }

    footer section div {
        flex-direction: column;
    }
}

@media (max-width: 480px) {
    section div {
        width: 100%;
        margin-bottom: 20px;
    }

    section button {
        width: 100%;
    }
}