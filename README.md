c;
    border-radius: 5px;
}

#contact-form button {
    padding: 10px;
    background: #2c3e50;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

#contact-form button:hover {
    background: #34495e;
}

footer {
    background: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}

footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}


---

javascript
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Спасибо за ваше сообщение! Я свяжусь с вами в ближайшее время.');
    document.getElementById('contact-form').reset();
});
```

---
