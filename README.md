<html>
    <style>
        label {
            display: inline-block;
            width: 190px; 
            vertical-align: top;
        }

        fieldset.kemampuan-dasar label {
            display: inline;
            width: 85%;
            margin-right: 2px; 
        }

        fieldset.kemampuan-dasar input {
            margin-right: 5px;
            }
        </style>
<head>
        <title>Form Registrasi</title>
    </head>
    <body>
        <body>
        <h1>Form Registrasi</h1>
            <fieldset>
                    <legend>Biodata</legend>
                    <p>
                        <label>Nama Mahasiswa </label>
                        <span>:</span>
                        <input type="text" name="Nama Mahasiswa" placeholder="Nama anda"/>
                    </p>
                    <p>
                        <label>No Induk Mahasiswa(NIM)</label>
                        <span>:</span>
                        <input type="text" name="No Induk Mahasiswa" placeholder="123456789"/>
                    </p>  
                    <p>
                        <label>Alamat Mahasiswa</label> 
                        <span>:</span>
                        <textarea id="alamat" name="Alamat Mahasiswa" rows="4" placeholder="Alamat Anda"></textarea>
                    </p> 
                    <p>
                        <label>Tanggal Lahir</label>
                        <span>:</span>
                        <select name="01">
                            <option value="01">01</option>
                            <option value="02">02</option>
                            <option value="03">03</option>
                            <option value="04">04</option>
                            <option value="05">05</option>
                            <option value="06">06</option>
                            <option value="07">07</option>
                            <option value="08">08</option>
                            <option value="09">09</option>
                            <option value="10">10</option>
                            <option value="11">11</option>
                            <option value="12">12</option>
                            <option value="13">13</option>
                            <option value="14">14</option>
                            <option value="15">15</option>
                            <option value="16">16</option>
                            <option value="17">17</option>
                        </select>
                        
                        <select  name="Januari">
                            <option value="Januari">Januari</option>
                            <option value="Februari">Februari</option>
                            <option value="Maret">Maret</option>
                            <option value="April">April</option>
                            <option value="Mei">Mei</option>
                            <option value="Juni">Juni</option>
                            <option value="Juli">Juli</option>
                            <option value="Agustus">Agustus</option>
                            <option value="September">September</option>
                            <option value="Oktober">Oktober</option>
                            <option value="November">November</option>
                            <option value="Desember">Desember</option>
                        </select>
                        
                        <select name="1990">
                            <option value="1990">1990</option>
                            <option value="1991">1991</option>
                            <option value="1992">1992</option>
                            <option value="1993">1993</option>
                            <option value="1994">1994</option>
                            <option value="1995">1995</option>
                            <option value="1996">1996</option>
                            <option value="1997">1997</option>
                            <option value="1998">1998</option>
                            <option value="1999">1999</option>
                            <option value="2000">2000</option>
                            <option value="2001">2001</option>
                            <option value="2002">2002</option>
                            <option value="2003">2003</option>
                            <option value="2004">2004</option>
                            <option value="2005">2005</option>
                            <option value="2006">2006</option>
                        </select>
                        <p>
                            <label>Jenis Kelamin</label>
                            <span>:</span>
                            <label><input type="radio" name="Jenis_Kelamin" value="Pria" /> Pria</label>
                            <label><input type="radio" name="Jenis_Kelamin" value="Wanita" /> Wanita</label>
                        </p>
                        <p>
                            <label>Upload Foto</label>
                            <span>:</span>
                            <input type="file" accept="image"/>
                        </p>
                        <p>
                            <label>Perguruan Tinggi</label>
                            <span>:</span>
                            <input type="text" name="Perguruan Tinggi" ></textarea>
                        </p>
                        
                    </fieldset>

                </tabel>
           
            <fieldset>
                <legend>Info Akun</legend>
            
            <p>
                <label>Email:</label>
                <span>:</span>
                <input type="text" name="Email" placeholder="Email Anda"/>
            </p>
            <p>
                <label>Username:</label>
                <span>:</span>
                <input type="text" name="Username" placeholder="Username Anda"/>
            </p>
            <p>
                <label>Password:</label>
                <span>:</span>
                <input type="password" name="password" placeholder="Password anda"/>
            </p>
            <p>
                <label>Ulangi Password</label>
                <span>:</span>
                <input type="password" name="password" placeholder="Password Anda"/>
            </p>
        </fieldset>
        <form action="" method="post"></form>
            <fieldset class="kemampuan-dasar">
                <legend>Kemampuan Dasar</legend>
                <p>
                    <input type="checkbox" name="checkbox1" value="checkbox1" id="checkbox1"><label for="checkbox1">HTML</label>
                    <input type="checkbox" name="checkbox2" value="checkbox2" id="checkbox2"><label for="checkbox2">CSS</label>
                    <input type="checkbox" name="checkbox3" value="checkbox3" id="checkbox3"><label for="checkbox3">JavaScript</label>
                    <input type="checkbox" name="checkbox4" value="checkbox4" id="checkbox4"><label for="checkbox4">PHP</label>
                    <input type="checkbox" name="checkbox5" value="checkbox5" id="checkbox5"><label for="checkbox5">MySQL</label>
                    <input type="checkbox" name="checkbox6" value="checkbox6" id="checkbox6"><label for="checkbox6">Laravel</label>
                    <input type="checkbox" name="checkbox7" value="checkbox7" id="checkbox7"><label for="checkbox7">React Native</label>
                </p>
            </fieldset>

            
                <input type="reset" value="Reset">
                <input type="submit" value="Simpan">
                <input type="button" value="Button">
            </form>
            
        </body>
    </html>
