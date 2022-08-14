<h1>PETUNJUK INSTALASI</h1>
<p> Program koperasi merupakan program berbasis website yang ditunjukkan untuk memudahkan koperasi sekolah dalam mencatat data penjualan barang dari koperasi tersebut.</p>
<p>Program ini dibuat dengan menggunakan: </p>
<ul>
    <li>Python (FastAPI, PyMySQL, fpdf2, pyinstaller)</li>
    <li>HTML, CSS, JS (JQUERY)</li>
    <li>MySQL</li>
</ul>
<ol>
    <li>Install XAMPP di komputer.</li>
    <li>Tambahkan 
        <pre>
            <!-- <IfModule mod_mime.c>
                AddType text/javascript js mjs
            </IfModule> -->
        </pre>
        pada httpd.conf
    </li>
    <li>import file schema database dari folder DATABASE ke MySQL</li>
    <li>Pindahkan file didalam folder FRONTEND ke dalam folder c:\xampp\htdocs\program_koperasi\</li>
    <li>Jalankan file Main.exe di folder REST_API</li>
    <li>Buat user baru secara manual di MySQL Shell</li>
</ol>
