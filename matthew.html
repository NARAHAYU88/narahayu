<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Ayu Medica Center</title>

<style>
/* ================= GLOBAL ================= */
body{
    margin:0;
    font-family:'Segoe UI', sans-serif;
    background:#f3f4f6;
}
.layout{
    display:flex;
    min-height:100vh;
}

/* ================= SIDEBAR ================= */
.sidebar{
    width:240px;
    background:linear-gradient(180deg,#6a5acd,#4b3fbf);
    color:white;
    padding:20px;
}
.sidebar h2{
    text-align:center;
    margin-bottom:30px;
}
.sidebar a{
    display:block;
    padding:12px;
    margin-bottom:10px;
    color:white;
    text-decoration:none;
    border-radius:8px;
    cursor:pointer;
}
.sidebar a:hover{
    background:rgba(255,255,255,0.2);
}

/* ================= CONTENT ================= */
.content{
    flex:1;
    padding:25px;
}

/* ================= CARD ================= */
.card{
    background:white;
    border-radius:12px;
    padding:20px;
    margin-bottom:20px;
    box-shadow:0 4px 12px rgba(0,0,0,0.08);
}

/* ================= SECTION ================= */
section{display:none;}
section.active{display:block;}

/* ================= FORM ================= */
input, select, textarea, button{
    width:100%;
    padding:10px;
    margin-top:6px;
    margin-bottom:12px;
    border-radius:6px;
    border:1px solid #ccc;
}
button{
    background:#6a5acd;
    color:white;
    border:none;
    cursor:pointer;
}
button:hover{opacity:0.9;}
.btn-hapus{background:#e74c3c;}

/* ================= TABLE ================= */
table{
    width:100%;
    border-collapse:collapse;
}
th, td{
    border:1px solid #ddd;
    padding:8px;
    text-align:left;
}
th{
    background:#f0f0f0;
}

/* ================= GAMBAR BULAT ================= */
.gambar-container{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
    margin-top:20px;
}
.gambar-container img{
    width:140px;
    height:140px;
    object-fit:cover;
    border-radius:50%;
    border:4px solid #6a5acd;
    transition:0.3s;
}
.gambar-container img:hover{
    transform:scale(1.1);
}

/* ================= FOOTER ================= */
footer{
    text-align:center;
    color:#777;
    margin-top:30px;
}
</style>
</head>

<body>

<div class="layout">

<!-- ================= SIDEBAR ================= -->
<aside class="sidebar">
    <h2>Ayu Medica</h2>
    <a onclick="showSection('beranda')">🏠 Beranda</a>
    <a onclick="showSection('layanan')">💉 Layanan</a>
    <a onclick="showSection('dokter')">👨‍⚕️ Dokter</a>
    <a onclick="showSection('kontak')">📞 Kontak</a>
    <a onclick="showSection('daftar')">📝 Pendaftaran</a>
    <a onclick="showSection('data')">📊 Data Pasien</a>
</aside>

<!-- ================= CONTENT ================= -->
<main class="content">

<section id="beranda" class="active">
<div class="card">
<h2>Tentang Klinik</h2>
<p>
Ayu Medica Center adalah pusat layanan kesehatan premium dengan standar medis
berkelas internasional. Kami menghadirkan layanan personal, fasilitas modern,
dan tenaga medis profesional demi kenyamanan dan kepercayaan pasien.
</p>

<div class="gambar-container">
    <img src="ayu1.jpg">
    <img src="ayu3.jpg">
    <img src="ayu4.jpg">
    <img src="ayuu3.jpg">
</div>
</div>
</section>

<section id="layanan">
<div class="card">
<h2>Layanan Klinik</h2>
<ul>
<li>Executive Medical Check-Up</li>
<li>Poli Jantung & Pembuluh Darah</li>
<li>Poli Ibu & Anak</li>
<li>Poli Estetika Medis</li>
<li>Poli Saraf & Neurologi</li>
<li>Konsultasi Dokter Spesialis</li>
<li>Laboratorium Klinik</li>
</ul>
</div>
</section>

<section id="dokter">
<div class="card">
<h2>Dokter</h2>
<p>👨‍⚕️ dr. Martin – Penyakit Dalam</p>
<p>👩‍⚕️ dr. Ayu – Spesialis Jantung</p>
<p>👨‍⚕️ dr. Daniel – Spesialis Saraf</p>
<p>👩‍⚕️ dr. Rahayu – Kesehatan Mental</p>
<p>👨‍⚕️ dr. Satya – Dokter Umum</p>
</div>
</section>

<section id="kontak">
<div class="card">
<h2>Kontak Klinik</h2>
<p>📍 Jl. Sehat No.10</p>
<p>📞 0812-3456-7890</p>
</div>
</section>

<section id="daftar">
<div class="card">
<h2>Form Pendaftaran Pasien</h2>
<form onsubmit="simpanData(event)">
<label>Nama</label>
<input type="text" id="nama" required>

<label>Umur</label>
<input type="number" id="umur" required>

<label>Jenis Kelamin</label>
<select id="jk">
<option>Laki-laki</option>
<option>Perempuan</option>
</select>

<label>Keluhan</label>
<textarea id="keluhan"></textarea>

<button type="submit" id="btnSubmit">Daftar</button>
</form>
</div>
</section>

<section id="data">
<div class="card">
<h2>Data Pendaftaran</h2>
<table>
<thead>
<tr>
<th>Nama</th>
<th>Umur</th>
<th>JK</th>
<th>Keluhan</th>
<th>Aksi</th>
</tr>
</thead>
<tbody id="dataTable"></tbody>
</table>
</div>
</section>

<footer>
&copy; Ayu Medica Center 2026
</footer>

</main>
</div>

<script>
let dataPasien=[];
let editIndex=-1;

function showSection(id){
document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));
document.getElementById(id).classList.add('active');
}

function simpanData(e){
e.preventDefault();
let pasien={
nama:nama.value,
umur:umur.value,
jk:jk.value,
keluhan:keluhan.value
};
if(editIndex==-1){
dataPasien.push(pasien);
alert("Pendaftaran berhasil!");
}else{
dataPasien[editIndex]=pasien;
editIndex=-1;
btnSubmit.innerText="Daftar";
alert("Data diperbarui!");
}
tampilkanData();
e.target.reset();
showSection('data');
}

function tampilkanData(){
dataTable.innerHTML="";
dataPasien.forEach((p,i)=>{
dataTable.innerHTML+=`
<tr>
<td>${p.nama}</td>
<td>${p.umur}</td>
<td>${p.jk}</td>
<td>${p.keluhan}</td>
<td>
<button onclick="editData(${i})">Edit</button>
<button class="btn-hapus" onclick="hapusData(${i})">Hapus</button>
</td>
</tr>`;
});
}

function editData(i){
let p=dataPasien[i];
nama.value=p.nama;
umur.value=p.umur;
jk.value=p.jk;
keluhan.value=p.keluhan;
editIndex=i;
btnSubmit.innerText="Update";
showSection('daftar');
}

function hapusData(i){
if(confirm("Hapus data?")){
dataPasien.splice(i,1);
tampilkanData();
}
}
</script>

</body>
</html>
