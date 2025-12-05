# QyF-UC
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Malla Académica - Farmacia</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f4f6f9;
        margin: 0;
        padding: 20px;
    }
    h1 {
        text-align: center;
        color: #083d77;
    }
    .semestre {
        background: white;
        padding: 20px;
        margin: 20px auto;
        border-radius: 10px;
        max-width: 900px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    h2 {
        color: #085dad;
        margin-top: 0;
    }
    table {
        width: 100%;
        border-collapse: collapse;
        margin-top: 10px;
    }
    th {
        background: #085dad;
        color: white;
        padding: 10px;
        text-align: left;
    }
    td {
        border: 1px solid #ddd;
        padding: 8px;
        background: white;
    }
    tr:nth-child(even) td {
        background: #f0f4ff;
    }
    .prereq {
        color: #444;
        font-size: 0.9em;
    }
</style>
</head>
<body>

<h1>Malla Académica – Química y Farmacia</h1>

<!-- 1 Semestre -->
<div class="semestre">
<h2>1° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>General 1</td><td>QIM100</td><td>—</td></tr>
<tr><td>Precalculo</td><td>MAT1000</td><td>—</td></tr>
<tr><td>Mundo medicamentos</td><td>QIF117</td><td>—</td></tr>
<tr><td>Introducción a las Ciencias Farmacéuticas</td><td>QIF100B</td><td>—</td></tr>
<tr><td>Laboratorio Química General</td><td>QIM101L</td><td>—</td></tr>
</table>
</div>

<!-- 2 Semestre -->
<div class="semestre">
<h2>2° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>General 2</td><td>QIM100B</td><td>QIM100</td></tr>
<tr><td>Cálculo 1</td><td>MAT1100</td><td>MAT1000</td></tr>
<tr><td>Física para Ciencias</td><td>FIS109C</td><td>—</td></tr>
</table>
</div>

<!-- 3 Semestre -->
<div class="semestre">
<h2>3° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Orgánica 1</td><td>QIM102B</td><td>QIM100 o QIM100B</td></tr>
<tr><td>Botánica</td><td>QIF115A</td><td>—</td></tr>
<tr><td>Estadística</td><td>EYP2310</td><td>MAT1100</td></tr>
<tr><td>Biología</td><td>BIO104C</td><td>—</td></tr>
</table>
</div>

<!-- 4 Semestre -->
<div class="semestre">
<h2>4° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Orgánica 2</td><td>QIM103A</td><td>QIM102B</td></tr>
<tr><td>Analítica 1</td><td>QIM109B</td><td>EYP2310 y QIM100B</td></tr>
<tr><td>Fisiología</td><td>BIO135C</td><td>—</td></tr>
</table>
</div>

<!-- 5 Semestre -->
<div class="semestre">
<h2>5° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Laboratorio Orgánica</td><td>QIM104A</td><td>QIM103A</td></tr>
<tr><td>Bioquímica</td><td>QIM117B</td><td>QIM103A</td></tr>
<tr><td>Química Física</td><td>QIM150</td><td>FIS109C</td></tr>
<tr><td>Análisis Instrumental</td><td>QIM111</td><td>QIM109B</td></tr>
</table>
</div>

<!-- 6 Semestre -->
<div class="semestre">
<h2>6° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Microbiología</td><td>BIO145C</td><td>BIO135C</td></tr>
<tr><td>Farmacoquímica 1</td><td>QIF101A</td><td>QIM104A</td></tr>
<tr><td>Fármacocinética y Biofarmacia</td><td>QIF104A</td><td>QIM150</td></tr>
<tr><td>Farmacología 1</td><td>QIF150</td><td>QIM117B</td></tr>
</table>
</div>

<!-- 7 Semestre -->
<div class="semestre">
<h2>7° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Farmacoquímica 2</td><td>QIF102A</td><td>QIF101A</td></tr>
<tr><td>Tecnología Farmacéutica 1</td><td>QIF105A</td><td>QIM111</td></tr>
<tr><td>Farmacología 2</td><td>QIF116</td><td>QIF150</td></tr>
<tr><td>Bioquímica Clínica</td><td>QIF118A</td><td>QIF150</td></tr>
</table>
</div>

<!-- 8 Semestre -->
<div class="semestre">
<h2>8° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Toxicología</td><td>QIF108</td><td>QIF116</td></tr>
</table>
</div>

<!-- 9 Semestre -->
<div class="semestre">
<h2>9° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Farmacoquímica 3</td><td>QIF103A</td><td>QIF116</td></tr>
<tr><td>Farmacia Clínica</td><td>QIF110A</td><td>QIF116</td></tr>
<tr><td>Farmacología 3</td><td>QIF111A</td><td>QIF116</td></tr>
<tr><td>Tecnología Farmacéutica 2</td><td>QIF106A</td><td>QIF105A</td></tr>
</table>
</div>

<!-- 10 Semestre -->
<div class="semestre">
<h2>10° Semestre</h2>
<table>
<tr><th>Asignatura</th><th>Código</th><th>Prerrequisitos</th></tr>
<tr><td>Salud Pública para Farmacia</td><td>MEB231Q</td><td>QIF150</td></tr>
<tr><td>Farmacia Privada</td><td>QIF109A</td><td>QIF116</td></tr>
<tr><td>Legislación y Deontología Farmacéutica</td><td>QIF107</td><td>QIF150</td></tr>
</table>
</div>

</body>
</html>
