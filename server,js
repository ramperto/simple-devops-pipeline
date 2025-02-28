const express = require('express');
const app = express();
const PORT = 5000;

app.get('/welcome/:nama?', (req, res) => {
    const name = req.params.nama || 'Anonymous';
    res.send(`Selamat datang ${name}`);
});

app.listen(PORT, () => {
    console.log(`Server running on port ${PORT}`);
});