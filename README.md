# COBOLWORK03
<p>DELDEF ile oluşturduğumuz VSAM.AA dosyasındaki kişi verileriyle QSAM.INP dosyasındaki key değerlerini karşılaştırarak eşleşen kişileri QSAM.OUT dosyasına yazan COBOL programı. Dosya detayları:</p>
<ul>
  <li>QSAMBBJ.jcl</li>
    <ul>
      <li>Kişi verilerini ilk 8 karakterine göre büyükten küçüğe sort ederek QSAM.BB dosyasına yazdırır.</li>
    </ul>
  <li>SORTEG03.jcl</li>
    <ul>
      <li>Anahtar değerlerinin olduğu QSAM.INP oluşturur.</li>
    </ul>
  <li>DELDEF.jcl</li>
    <ul>
      <li>VSAM.AA dosyamızı oluşturur.</li>
    </ul>
  <li>VSAMJ.jcl</li>
    <ul>
      <li>VSAMCBL kaynak kodunu derleyerek uygun outputları QSAM.OUT dosyasına yazdırır.</li>
    </ul>
  <li>VSAMCBL.cbl</li>
    <ul>
      <li>Tüm kaynak kodlarını içeren cbl dosyası</li>
    </ul>
</ul>
