# lab3web
### Nama: M. Rizqy Al Rasyd
### Nim : 312410424
### Kelas : TI.24.A3

## Soal dan jawaban
![gambar](soal_form_dropdown.png)

1. Form
```
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <form action="proses.php" method="post"> 
        <fieldset>
            <legend>Login</legend>
            <p>
                <label for="uname">Username</label>
                <input type="text" id="uname" name="Username">
            </p>
            <p>
                <label for="passwd">Password</label>
                <input type="password" id="passwd" name="password">
            </p>
```

2. Dropdwon
```
<p>
                <label for="gndr">Gender</label>
                <select name="gender" id="gender">
                    <option value="Laki-laki">Laki-laki</option>
                    <option value="Perempuan">Perempuan</option>
                </select>

            </p>
```

3. Listbox
```
<label for="Listbox">Listbox</label>
                <table border="1" cellpading="6" cellspading="0">
                    <thead>
                        <tr>
                            <th>No.</th>
                            <th>Pilih Matkul</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1.</td>
                            <td><input type="checkbox" name="Matkul" value="Pemrogramana Web">Pemrograman Web</td>
                        </tr>
                        <tr>
                            <td>2.</td>
                            <td><input type="checkbox" name="Matkul" value="Statistika">Statistika</td>
                        </tr>
                        <tr>
                            <td>3.</td>
                            <td><input type="checkbox" name="Matkul" value="Basis Data">Basis Data</td>
                        </tr>
                        <tr>
                            <td>4.</td>
                            <td><input type="checkbox" name="Matkul" value="jaringan Komputer">Jaringan Komputer</td>
                        </tr>
                    </tbody>
                </table>
```
### Screenshot VScode
# 1. Form
![gambar](form.png)

# 2. Dropdown
![gambar](dropdown_code.png)

# 3. Listbox
![gambar](listbox.png)

### Hasil
![gambar](Hasil.png)
