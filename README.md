# V1.0 pradinė
Programa apdoroja pasirinktus studentų failus ir skaičiuoja veikimo spartą naudojant skirtingus konteinerius: vector, list, deque.<br>
Testas atliekamas su CPU Intel Core i5, Tiger lake 11-a karta, 6 branduoliai, dažnis 2.7. GHz. Maksimalus operatyviosios (RAM) atminties kiekis 32 GB, taktinis dažnis	3200 MHz. Kietasis diskas	SSD (samsung mzalq512hblu-00bl2) M.2 2242 NVMe PCIE 3, talpa	512 GB. <br>
## Strategijos
**Pirma strategija:**<br>
Programos testavimas su VECTOR:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/b3416ac6-acc5-4152-a278-5ab1a5a52c76)<br>
Programos testavimas su LIST:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/7e46cc2c-0f8d-44b8-9a8f-5b064f3c642c)<br>
Programos testavimas su DEQUE:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/2ad11dc4-2315-4528-9d11-eccd7ceff55d)<br>
<br>
**Antra strategija:**<br>
Programos testavimas su VECTOR:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/a51d086a-1ca1-47cd-9963-07641ca27103)<br>
Programos testavimas su LIST:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/09d34863-8ce1-4165-9fc5-91edcaa4df53)<br>
Programos testavimas su DEQUE:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/d51f5859-031c-4367-8bd3-fd485590a3cc)<br>
<br>
**Trečia strategija:**<br>
Programos testavimas su VECTOR:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/52457ce0-9550-4a32-a9d9-4f088211664c)<br>
Programos testavimas su LIST:<br>
![image](https://github.com/EligMaa/Darbas_1/assets/151032480/bd6d4822-565b-4587-9564-9a147f90d829)<br>
Programos testavimas su DEQUE:<br>
![Uploading image.png…]()<br>
<br>
## Naudojimo instrukcija
Paleidus programą egzistuoja meniu, kur vartotojas gali pasirinkti kaip nori dirbti su duomenimis:<br>
1 - duomenų įvedimas<br>
2 - duomenų skaitymas iš failo<br>
3 - programos laiko testavimas naudojant failų generavimą<br>
4 - programos laiko testavimas naudojant failų rūšiavimą<br>
5 - baigti darbą<br>
<br>
Pasirinkus **1** variantą vartotojas gali pasirinkti kaip įvesti studentų duomenis:<br>
1 - įvedimas ranka <br>
2 - generuoti pažymius <br>
3 - generuoti ir pažymius ir studentų vardus, pavardes<br>
4 - baigti darbą<br>
Gaunami duomenys yra įrašomi programos pabaigoje į lentelė su studentų vardais, pavardėmis ir jų galutiniais įvertinimais (jie skaičiuojami pasirinkus medianą ar vidurkį).<br>
<br>
Pasirinkus **2** variantą vartotojas gali pasirinkti su kuriuo duomenų failu nori dirbti:<br>
1 - iš sugeneruoto duomenu failo 'kursiokai.txt'<br>
2 - iš testavimo failo su 10000 studentų duomenų<br>
3 - iš testavimo failo su 100000 studentų duomenų<br>
4 - iš testavimo failo su 1000000 studentų duomenų<br>
5 - baigti darbą<br>
Duomenys yra nuskaitomi iš pasirinkto failo. Vartotojas taip pat turi galimybę pasirinkti kaip nuskaityti failai bus rūšiuojami:<br>
1 - pagal studento vardą<br>
2 - pagal studento pavardę<br>
3 - pagal studento galutinį įvertinimą su vidurkiu<br>
4 - pagal studento galutinį įvertinimą su mediana<br>
<br>
Pasirinkus **3** variantą vartotojas gali testuoti pogramos laiką, kuriant pasirinkto dydžio failus:<br>
1 - su 1000 studentų duomenų<br>
2 - su 10000 studentų duomenų<br>
3 - su 100000 studentų duomenų<br>
4 - su 1000000 studentų duomenų<br>
5 - su 10000000 studentų duomenų<br>
6 - baigti darbą<br>
<br>
Pasirinkus **4** variantą vartotojas gali testuoti pogramos laiką, rūšiuojant failus su pasirinktu konteineriu:<br>
1 - vector<br>
2 - list<br>
3 - deque<br>
4 - baigti darbą<br>
