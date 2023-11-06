# 2023-11-07

- negaun atcakimo **neveikia**
- JavaScript kalba:

```
const meniuBtnEditOn = document.querySelector(".btnEditCancel > button");
const meniuBtnEdit = document.querySelector(".edit");
const meniuBtnCancel = document.querySelector(".cancel");

meniuBtnCancel.addEventListener("click", () => {
  console.log('btn Cancel');
  meniuBtnEdit.classList.remove("on");
});
meniuBtnEdit.addEventListener("click", () => {
  console.log('btn Edit');
  meniuBtnEdit.classList.add("on");
});


meniuBtnEditOn.addEventListener("click", () => {
  if (meniuBtnEdit.classList.contains("on")) {
      console.log('veikia');
  } else {
    console.log('neveikia');
  };
});
```

- HTML kalba:
```
<div class="btnEditCancel ">
  <button class="edit">Edit</button>
  <button class="cancel">Cancel</button>
</div>
```

# 2023-11-06
- kol kas nėra klausimu 😊

# 2023-10-31
- kol kas nėra klausimu 😊
# 2023-10-30
- kol kas nėra klausimu 😊

# 2023-10-26
- kol kas nėra klausimu 😊
# 2023-10-25
- kol kas nėra klausimu 😊
# 2023-10-24
- kol kas nėra klausimu 😊
# 2023-10-23
- kol kas nėra klausimu 😊

# 2023-10-19
- ar būtu galina per tinkllapi koreguoti 3D modelio matmenis ir automatiškai ji sugeneruotu ir atvaizduotu klientui, failu pav. (SLDPRT, SLDASM) failai suikurti su SolidWorks programa
# 2023-10-18
- kol kas nėra klausimu 😊
# 2023-10-17
- kol kas nėra klausimu 😊
# 2023-10-16
- Kaip reiktu spresti ši uždavini?
- https://www.codewars.com/kata/577a6e90d48e51c55e000217/train/javascript

# 2023-10-12
- Kai tinklalapi priartinus viskas išsimieto tekstas ir t.t. kaip padaryti, kad nebutu išsimetitas
- Inrasius i <main ...display: inline-block;"> niekas nepasikeičia, ar ir neturi faktiškai kažkas matitis (display: inline-block)?
# 2023-10-11
- kol kas nėra klausimu 😊
# 2023-10-10
- kol kas nėra klausimu 😊
# 2023-10-09
- const binaryArrayToNumber = arr => {
  
  const binaryString = arr.join('');
  
  const decimalNumber = parseInt(binaryString, 2);
  
  return decimalNumber;
  
};

nesupratau kaip veikia ši vieta (parseInt(binaryString, 2))

# 2023-10-05
- nėra klausimu 😊
# 2023-10-04
- nėra klausimu 😊
# 2023-10-03
- nėra klausimu 😊
# 2023-10-02
- kaip greičiau suvirškinti ir isiminti visas paskaitas :)

# 2023-09-28
- koki preda reiktu atsisiusti, jei parašau pvz. a=1; ištaiso su tarpais a = 1;
# 2023-09-27
- neleidžia prisijungti prie https://www.codewars.com/users/sign_in
- kaip tai sutvarkiti nes nelaidžia nieko paspausti, pvz. pamiršau koda
# 2023-09-26
- kaip geriausisiai naudoti 'let' funkcija, kad nenulauztu mano sistemos, arba kada galeiau naudotis ir pagal ka ka tureciau orentuosis
- paskaitos metu pas jus buvo kitaip nei pas mane, kodel nera taik kaip pas jus? /* let y = 5;

let x = 7;

// x = x + ++a; // error

// x = x++ + a; // 14

x = x +++ a; // 14

console.log(x); */

Pas jus buvo tai: /* let y = 5;

let x = 7;

// x = x + ++a; // 13

// x = x++ + a; // 12

x = x +++ a; // pataise

console.log(x); */

# 2023-09-25
- test
