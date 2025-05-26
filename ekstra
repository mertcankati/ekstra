<!DOCTYPE html>
<html>
<body>
    <h2>başkanlar listesi</h2>
    <p id="demo"></p>
    <script>
    let text = '{"baskanlar":[' +
    '{"baskan":"berat","soyadi":"a" },' +
    '{"baskan":"nazar","soyadi":"b" },' +
    '{"baskan":"ecesu","soyadi":"c" },' +
    '{"baskan":"ahmet","soyadi":"d" },' +
    '{"baskan":"emre","soyadi": "e" }]}'; 

    const obj = JSON.parse(text);
    let output = "";

    for (let i = 0; i < obj.baskanlar.length; i++) {
        output += i + ": " + obj.baskanlar[i].baskan + " " + obj.baskanlar[i].soyadi + "<br>";
    }

    document.getElementById("demo").innerHTML = output;
    </script>
</body>
</html>
