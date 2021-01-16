# uas-deni-indriyanto-2010007
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Deni Indriyanto - 2010007</title>
    <style>
        * {
            font-family: Arial,Times new roman, sans-serif;
        }
        
        .wrap {
            width: 70%;
            display: flex;
            justify-content: space-between;
            margin: auto;
        }

        p {
            color: Pink;
        }

        .data_pemesan_tiket tr:nth-child(odd) {
            background-color: rgb(167, 230, 255);
            font-weight: bold;
        }

        .toggle-data {
            display: none;
        }

        .toggle-center {
            margin: auto;
        }

        #err_name, #err_jml_tiket {
            color: rgb(250, 57, 57);
            padding-top: 3px;
            font-size: 12px;
        }
    </style>
</head>
<body>
    <div class="wrap">
        <div class="toggle-center">
            <p>Online ticketing order Garuda airlines</p>
            <table border=0 cellpadding="20" cellspacing="10">
                <thead>
                   <form>
                        <tr>
                            <td>
                                Nama Pemesan
                            </td>
                            <td>
                               :
                            </td>
                            <td>
                                <input type="text" id="name">
                                <div id="err_name"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                Jumlah Tiket
                            </td>
                            <td>
                                :
                             </td>
                            <td>
                                <input type="number" id="jml_tiket">
                                <div id="err_jml_tiket"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                Kelas
                            </td>
                            <td>
                                :
                             </td>
                            <td>
                                <select name="kelas" id="kelas">
                                    <option value="eko">Ekonomi</option>
                                    <option value="bis">Bisnis</option>
                                    <option value="eks">Eksekutif</option>
                                </select>
                            </td>
                        </tr>

                        <tr>
                            <td>
                                Tujuan
                            </td>
                            <td>
                                :
                             </td>
                            <td>
                                <select name="tujuan" id="tujuan">
                                    <option value="Bali">Bali</option>
                                    <option value="Kalimantan">Kalimantan</option>
                                    <option value="Sulawesi">Sulawesi</option>
                                </select>
                            </td>
                        </tr>
                        <tr>
                            <td>Bagasi :</td>
                            <td>:</td>
                            <td>
                                <input type="radio" checked name="bagasi"  value="5kg"> 5 Kg
                                <input type="radio" name="bagasi"  value="10kg"> 10 Kg
                                <input type="radio" name="bagasi"  value="15kg"> 15 Kg
                            </td>
                        </tr>
                        <tr>
                            <td>
                                Asuransi 
    
