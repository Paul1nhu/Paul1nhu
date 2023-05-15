Minha página
<html>
  <head>
    <meta charset="UTF-8">
    <title>Minha Página</title>
    <style>
      .tabs {
        overflow: hidden;
        border: 3px solid #c8ff00;
        background-color: #3cf799;
      }

      .tablinks {
        background-color: inherit;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 14px 16px;
        transition: 0.3s;
      }

      .tablinks:hover {
        background-color: #ddd;
      }

      .tablinks.active {
        background-color: #ccc;
      }

      .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
      }
    </style>
  </head>
  <body>
    <div class="tabs">
      <button class="tablinks" onclick="openTab(event, 'perfil')">Perfil Pessoal</button>
      <button class="tablinks" onclick="openTab(event, 'hobbies')">Hobbies</button>
      <button class="tablinks" onclick="openTab(event, 'computacao')">Área da Computação</button>
    </div>
    <div id="perfil" class="tabcontent">
      <h3>Perfil Pessoal</h3>
      <p>Eu me chamo Paulo Junio, tenho 20 anos e moro na região do vergel desde que nasci.</p>
      <p>Gosto de animais e principalmente gatos. </p>
      <img src="https://lh3.googleusercontent.com/6qlZEC9XUjRWsFU2KmpeMa7-LkjD66XFk6-jsT1SuqP90qEGl3DKQ-OV3PL89O5d-xlkI50twC2Yo4KMNmw0n79hMniYvoJVbkI5FMCS1b-Amon0Pko0O4CYYTGPmAz3oY1nZTdd0yPxQY6-2XARSZTKiSehGXL82t-XqDZk6FAmKy5MOjLC25vZcUgKS2ukcdL7uROMN4AJ4PJOo_7fpy84h25dPH8tteQtq6uMIdyoFuKwpL40lqe4qqWfaKDh__Ze6cYSK1qg3cQGPccrlVd0nii98HSjHn5PjvQ-90mw8W2G_umC-proTHNAcvQvNRA07lWGdFCdoIiBrT5kERvDxDruZvJDFxn_6nyn9cYbBEfvVUE8W4zgUPqMyTS7iYowMDEWzz4i2qbGw5Ni-tW8mZitYyrYtaqfbJbkSfxdiz-qGwM2z-udXS1PoYfC_LucxJhok64XAw-ZQFg9ivxD-7qsxA3KzNPg8ecwmPvkCW4xMX_5gWRE0k5ivVsahUYm-W2febt5jOG3Iik0O-Mv00WSmc5hgOb2MkuayCf6sJ8wKQ1UzHeR6m0EtcsY1mHjIwjdTuVQVZ0VXHQ4gA_5qlbhVsnCaZGncp_lc82uGb76k5nc7RPPDI1dWq3PZgSU6M9cladFFuVXjO_jwhtzn3RTPa1i4LxFUHfr34vf-Rw2FLKGnRtmssj6JwK2tdKcp4lBt7xKAoptUH4N2kMY_VT0RYJhm4N_ktDzxsbZW79fKmFkeHSgHcfsK7CmH3merfO_m4rQVfn-I8CdM-ZNokUY95dpm_6cq2JsTnDFplq6TFlEN0WfkRQRwz9AC_by-IGKx3frUlhO68cUJf9A5CD08I4ur2I1YjF72J2eM_7qyUnAfWEQqVLgZWuRwdkRY75u17vsxekqoc7-g-X8tEggTIWAJK4dmxxsInpveTF7vurN6RdkbkYGguNLNq161KaHuK1qgoaLQJCJber9PPz2axezgX9IxP_lb6HexBXB5W1XkUwmraMoKQFpdnWZvZwujbnSLTJmkJtDboWxh0b4=w328-h437-no?authuser=0" alt="Minha gatinha" style="display: inline-block;">
        <img src="https://lh3.googleusercontent.com/YnyAynBFMtRJv8I_VOo6kwYC57_dlOb0pNG0PpFbdcrbuwr3ooefY4vQKMyhf5XhDDxuzT-RO7hdzvISUR4toU8Dp6gJH6N0pmRvfqNhvXuKmnTK4oq81Wihsw1vmiu8l4TjSI1Wc1BomLIOV3FwMlgo36V2b-k3-wHFL3yVt3BuADXONt8fjbC87nvDqCJ4aa-5PfAq-tysOBHsOt50wsZO8EpsmWLWgLM3YBoH28cIkaqsp8xAW7ldvITRb5NMh7jo-wXc8TXwGlIXmCLxvXoPUjguweB1WDgUQvl6jVI2dL77pjWhyYpvlCA45aJw3FeWvd07hs1iSFSHvGjddgYEtW34hkktJ_Im9UUVGxp44MffxxaMGJWgBCub8R29oftJnNVqT1ZeMUMPCliW02FhVCDuyhccAonCCMydCg_k9FWgC2OoTqWjNle3y0PeIZNyKjWWYrvvA8ST7r1hdPwi42VFy1s0A_nZUyPn_amQcGE9PI2NTkqVcEmLpJIjl5TcVR4OfAHLULCRlYVLeMoGhicwW89MCtR5mTqBETmReWF-81-nDLwK5nS5bKYhp3NFm5nWqyzPcHlUkZWVzma8viwqQUDYQWD60GnHdcJEnWAFl2WeJxSNL0A_LlzakZsMY-k_eambVU-N_hlWUTbHlW2xsFrz1lPFKKQv_qExjN-ZKo8sPad1XgX5T5eSQaPUFnMHqFTX2dR37mGczqinrTpgazg3cy3axaoHfLNAgXCSf3ivK9Roi6A_UkCKEkhPwB3q0TKv9juDdzGL_5OiUKBtmifvATJlOpdO7y_1TYR9C3yCgJE_gO0iF3x8Tr78uLrozOrFm6WA7zgK7eR5FZHAcN4XaT7RUlagdHKK6SqCkiKjS2kY1ie-aF7qV3N50SJnPMiG_RAd4Sdj2Uo77ErX9iVoM2tsRmFe-xNSErmSNWmuSh_4AtdGSwdRU4S7CWNcPbCTHr-yQa7cNJALM4GIki_udWQLXqS0tcDgPA75F3XhWzDFsxTgD0LUIXs6iWPVVyhC0kz1XqcPrSBjYSZK=w494-h658-s-no?authuser=0" alt="Uma fofa" style="display: inline-block;">
    </div>
    <div id="hobbies" class="tabcontent">
      <h3>Hobbies</h3>
      <p>Nao tenho nehum hobbie.</p>
    </div>
    <div id="computacao" class="tabcontent">
      <h3>Área da Computação</h3>
      <p>Fazer sites/apps/jogos.</p>
    </div>
    <script>
      function openTab(evt, tabName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
          tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
          tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(tabName).style.display = "block";
        evt.currentTarget.className += " active";
      }
    </script>
  </body>
</html>
