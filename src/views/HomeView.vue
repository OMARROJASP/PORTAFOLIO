<script setup>

</script>

<template>
  <div class="bg-gray-900">
    <h1 class="text-white text-center text-5xl">PORTAFOLIO</h1>
  </div>

  <div class="sm:grid sm:grid-cols-2 gap-4 p-10">
      
    <div class="flex justify-center">
      <img class="rounded-xl" src="../img/perfil.png" alt="No se cargo la imagen">
    </div>

    <div class="flex flex-col">
      <h1 class="font-semibold text-4xl felx flex -col">Mi P<p class="text-purple-500">erfil</p>
      </h1>
      <h1 class="text-justify">
      Soy estudiante de la Universidad Peruana de Ciencias Aplicadas(UPC). Estoy cursando el octavo 
      ciclo, en la carrera de ingenieria de Software. Tengo habilidades en programacion web, base de datos
      y diseño de aplicaciones. Me considero una persona que le gusta aprender nuevas tecnologias 
      y ponerlo en practica lo aprendido en los poryectos. Me gusta apoyar a mis compañeros,de la misma manera,
      acepto las criticas constructivas. Asimismo, me gusta trabajar en equipo y liderar el grupo 
      para llegar al objetivo del proyecto.
      </h1>

    </div>
  </div>

  <div class="bg-black text-center py-10">
    <h1 class="text-white font-bold pb-10 text-6xl">Mis Proyectos</h1>
    <div class="md:grid md:grid-cols-3   gap-4 ">
      <div class="text-white flex flex-col">
        <div class="bg-gray-900 mx-5 py-5 rounded-t-lg font-bold text-3xl">
          
          PokeApi
        
        <img src="../img/Captura de pantalla 2023-02-06 164649.png">
        
        </div>
        <div class=" bg-gray-800 mx-5 rounded-b-lg ">
          <p>
            En este proyecto mostramos una lista de pokemones que podemos elegir para seleccionarlos
            como favoritos y de la misma manera eliminarlo de la seccion de favoritos
            , este informacion se extrajo de atravez de una API.
           
          </p>
          <button class="
            hover:bg-purple-800 bg-purple-600 
            text-white font-semibold px-8 
            py-1 my-4 rounded-md"> <a  href="https://practica-pokemon-u201920341.netlify.app/pokemons">+ Info</a>
          </button>
          
        </div>

      </div>
      <div class="text-white flex flex-col">
        <div class="bg-gray-900 mx-5 py-5 rounded-t-lg font-bold text-3xl"> 
          
          LEASING
          <img src="../img/Captura de pantalla 2023-02-06 165626.png">
        </div>
        <div class=" bg-gray-800 mx-5 rounded-b-lg">
          <p>
            En este proyecto mostramos una lista de ventas de combustibles
            y un formulario para llenar datos. Estos datos lo guardamos en una 
            base de datos en FireBase. De la misma manera tiene autentificacion 
            a travez de FireBase.
          </p>
          <button class="
            hover:bg-purple-800 bg-purple-600 
            text-white font-semibold px-8 
            py-1 my-4 rounded-md"> <a  href="https://practica-pokemon-u201920341.netlify.app/pokemons">+ Info</a>
          </button>
        </div>
      </div>
      <div class="text-white flex flex-col">
        <div class="bg-gray-900 mx-5 py-5 rounded-t-lg font-bold text-3xl"> 
          
          Registro de Ventas
          <img src="../img/Captura de pantalla_20230207_114458.png">
        </div>
        <div class=" bg-gray-800 mx-5 rounded-b-lg">
          <p>
            En este proyecto mostramos una lista de ventas de combustibles
            y un formulario para llenar datos. Estos datos lo guardamos en una 
            base de datos en FireBase. De la misma manera tiene autentificacion 
            a travez de FireBase.</p>
            <button class="
            hover:bg-purple-800 bg-purple-600 
            text-white font-semibold px-8 
            py-1 my-4 rounded-md"> <a  href="https://finanzas-2022-2.web.app/">+ Info</a>
          </button>
          
        </div>
      </div>
    </div>
  </div>

  <div class="text-center py-10 ">
    <h1 class="text-6xl font-bold  py-10">Lenguajes</h1>

    <div class="grid grid-cols-3 gap-4 mx-10
     text-center">
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/226/226269.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/5968/5968242.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/5968/5968282.png" alt="No carga la imagen">
        </div>
       <!---->
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/1199/1199124.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/6132/6132222.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/5968/5968672.png" alt="No carga la imagen">
        </div>
         <!---->
         <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="data:image/png;base64,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" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="data:image/png;base64,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" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="data:image/png;base64,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" alt="No carga la imagen">
        </div>

    </div>
    <div class="grid grid-cols-3 gap-4 mx-10 py-4">
      <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/919/919836.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="https://cdn-icons-png.flaticon.com/128/919/919825.png" alt="No carga la imagen">
        </div>
        <div class=" flex border-2 rounded-md  justify-center py-20">
          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAABKVBMVEX///9DmTRFpThAlDNGoDdPqkFXrkdKpzxgsk+Uel7+/f1QOCxSq0T8+/uUeFqTel708u+6qJbu6uafgmRPNihPNyxPNSdZrkrg3NqGd3BGKhpFpzjz8O3l4uBQOi1DJhHDvLlZQTT2+vXCwaeZgWaznojOycZtWU/Jw8DUyb5JMCChl5LR5c7j8eFLoD3y+PGsqovMy7SpknqyqaXN5shosVy3tpnc28jIu6+9rp7Yz8WRhH5fSDtrVkuek42Fdm53Zl6727SczJNzvmOQw4ip1KKGwX07oydxv2G0161/wnPD379Vs0Ok0Z2m1KB0uWlapE52sW2HuYB8s3Q6qClQnEQ0lSNpqVddm018qmaSrHhvnlugrIKDomp6qmNlq1qtupY2DAA+HAEdo0aAAAAR8klEQVR4nO2dCVvbRhrHbcc2IFlghCzLh2SLgA8ZA0UkwUg+QhIIR0rabmi3m+7B9/8Q+87oGp12uqHWePm3eR6ERvL89L7zHiOnzWSe9axnPWvVtLu77Bk8tU5Plz2Dp9bbixU34u7F+sGy5/C0Gr5rvF9tI34oVgsrbcTT9fX1xiWz7Gk8nYYfgTCfW10jDu+LQHiYe7XsiTyVDt4hwPV8/urtsqfyNDr9iAHXD/P5w+GyJ/MUOrUsiAkblyuYMW5tC2LC/NrqVTYeICbMlz6sGOLtx3VXpTxGvF4pRBLQsiE46vWyZ/Ud5QN0CPON1UE89QG6hKuTFoc3RR9hySHMP9wue27fRbsXd3GE+epKNPzXd0U/YdUjzL1agSL8dL1YLFZjCPO5e+rrt6N3BSAsxhFC/Xa07Cn+j7q5qyYS5huf6O6Hf7QAfYh+Qspzxi0swuocwlyD4qUIPb2jeMJ84xW1FerRexeQjKalfBDxYtkz/bNCPhphxBBhvkBpbTO8KVSjjBgmpDMrMpm3DZKwmECYz1HZ8h99vEOE1RBhMNJQ66c/NkqFYjXChlGENPrpsFgoFSIXYhRhvkHfvs1lo+QnLCYS5qq0GXF4V0CKctNIQijBlz3lb9RlAxNGuWk0Yb5BVzd8WiyECItzCKl6X7N7Y5uwUAq7aQxh/oqmjPH2rlCINWIcYY6iCvzocs0jDBkxjjC/Rk+neLBecgnDbhpLmLunZkfjGufCODeNJcyXaFmJQ4gzxT9DmKNlW+qgsLaW4KYJhJR8m2j3UwMIS1GExWTC/MMnKsLpcB0I1zw3LS5OSIkRbxFgjnBTgrCaTJjP0ZAwdi8RYYKbJhLeUBBrhgVM6LhpKeSmSYT5PAVu+uEKA8ZE0+ocwisKNvk/WiZcK8S5aSJhbj310fTgqrAWNOI3EOavUu+mF38rOYQuYtHvpomE6e/17xsOYSHOiDFsh/lDUPZw2QRzNCw11iLctJpIeGgri/SQ8t2M27tcrhBy01IcoY/NUu79shmSddHwCJGblsJuWiXYshH6nO5oegOEjpvGLMRqHJqtfKrddPgq5xHGJf0kPOSmn5ZNkaTTIhD63DRsxHmE2Z+WTZGk67tcLtpNq4sTfk7zBv+nRi7gpqWQm84lrKZ4uwY6p9xcN51LmP+wbI54De9twqSkP5cw+3N688XBR4swMZrOJ/wpvQvxdD2Xi3HTbyDMp/gbi2/vGjm/m0bsm8634WF6Q811wyZcS6hN5xPm0/sN8E9XufluOp8wvdumR+8bLmF8NJ1PmP05rTtuR5cuYS7c6ZcWJ/wlrcF0eBMmDLvpAuswtd+uGb7zCKPcdGHCV2kldBK+L9aENqQWIUxrQjyoRhCGatMFCFP7guagSBDGbkgtEGkO00p4WogkDMYamgkbBCHppiWfm84FpIUwbkOqRDNhIYow6KarQxgXTWkm9MXS2A2pKs2E65GEgU6f5mzhq2li3ZRmQrIujatNq4sQVlNLeO8njHbTBaq2z6klvPETRnf6NPcWZAfsI/R9Q4rm/nD3IkAYlfQXIUzvhul1gDDKTanep8m8XQsShvdNi+sU77VlTteDRgxvSBWo3i89eBdHSCT9Es173qFgGpX051be+fUUv8kPBtOoDanCPMLsv1IbSp233DHRtLQo4S+pDaWouwgShiu3+f1hmr+McXQ/302TIs2L7IsXL76kN9CA3jdCKTHopjGEL1yleRmid6RxblqIs+HhC7+yvywbIlFHpaCbkrVpyU/4IlL5NC9D0M1Vgps6NjwM2o1UivM91tu/BQmDblpKwkOBJrVFqaXdxjw3rX5JBEz5MgRdznPTUrIJH1L/12ZOr3JBIzpaiDCb4oLG0m6ovwh8kS95Gab7u5eWrkNG9LtpNdlJ07rNRmhYjW2hinMJs/9KvZNmmN2LoBHXSuRCTPTSh/S294QOwkYk3TSJMN3fD3Z1FOqDfZ1+ImF696B8OkjckEogzH6hIM4g7b5PcNOkoi37Pv1xxlKo1SdTYgJhuntfn2KNCG4aT5jive6QhiU/YINw03jCtPdNPn0INFFEgxFLmP6uwqdgOHUJi7GEqX23Ha3TRsw7/Woc4cPPy57zN4nJBGo3100LcT56SE+YsRR8qT+PMP2db0in/u8POZVbDOHDT3TUa6SYD1dRbhq9DLNU/m9Lji6vIgh/jdyIAh9N/38uIiz/d6Rswn/+FmVCagrSgG7vGkEjFv4eQZjmv602R+RStAhLf4QJs6n9DtR87ZJL0SL8/R/h9xX0JQpPR/ceIs4X1a9/hKIMff91VlJDL9ogN82FCR9+oTGKEiK+OIwIP3/9PQB4T7UFkbxdG3DT3K/HX30JMUthLROS902p0lrj1+Pj33yAlCZCv26dDVRw038eH/9jJRKhX7cF92+x/3F8/Ed25QC9frhU+v34+OsKAkK4seq3QvXr8fHr3ywjPlDwFuYbZCcNCDTHL78+WIArEEVJ4Z6/AYHm9euXX7KonVj2jL67hpewGH9HhK///SX7meZaNE5HF43DY2zDH/79M73dRJJ2r3/FJnz58ofysufyVPrBJnyz7Ik8mZrYSV++XFkTZrjXlpMuex5PJ+bNijtpJsNjE/LLnsYTavUJyxBmVpzwBwBc3WwI4t4gwhUruX1iMCHlm2vJkgFwhdMhiAfCVU6H/xeEALjahOU3q0/45pmQcpXBSd+sdD7cBUB+lWsaUJk/4pY9h6cWt9Je+qxnzXdwhv41sADkXzCL76Dy/uYe6ARrz9LJdp/nSAI5YkSTDkQmc76zs+loB8n++QQQbAKGO/MGeT+NqNgHYjL8eX90soG0t32GNNo/2djc2ADGcyehMjIM2nPGjLb38QUwgA4jgvh9NOP9pvWrstTf38SMoyYxsr8DY06Q3ZimNNpDA07kv37C3y6MeLazsbW57fHw/ZNNZKXtprfWeAS1b3smd4ateEZN2dTf2dpwCVEeYCQLceQhNIFw0yZkMtz2pmNSKtTHNiT2V2F9IsTNnb5rRLDhlkMIktDpPekvnuif1jlpQ1uWFb2l1oRQ4xKCEbGbUkZY9odG5Lpoqdm/bZI2ZDIMiq1PZsNQkF4wascOO9/ZCBIymfIJTgmOX5Lr0LLh1mbEOrTuUZZwjGpKnY7Eub/rdDrBC9Cal+H3HSkUl2U8mJN67bb/MnQ7dOeOxNsztq3A2B8JZ4JvNCII4T5nyIgb51GEsCxjY2lZ6umTbhuGtI2uac4GMn5e6EAdG73AJeXOYDo2VbM71QmHaErtQW0M9+hMZqommrWO7yJJN2amaXZregeKL07SnZgvoxOqOp4Z7bLPoNGE/Cayk0PBO4QM/vfMx+upM6nNTEETe5neFObGsoI4A8SOYcKBIoim7kOUjHFLHJtaXRTFrm5FAq5t1LqmpoltTu+iW7CsNu558yrrM1GdTscaXDOeGobRHVsTgRNCyxwrLVHQ1JpvBUWuw0wGmLwQi2OpG43O9zYRYNjvJ/+pw5wUQdfVljoW6jA9ccoNzHoL/hEAWCHMweljsT7gm7w0YcWKwE7w7fnZI7qMNQeG0Gq16mKlwgpdd8K8odQNvlxu6gKrKKIGmlknZkp92uGbcrtbV1it2yGmF2VDOL2PMsK+TYi8dONE4ptlnj+HmmavH7mJwMiGih67IBgdjuF0EaYhmpo6kJp829RgSjPvc3R4GjZwRxUrbH2A79kE8ApirHd1SWrX4B4VcWJfUzY0cWwtxjaAAGTdxGuYB7Mb1mSbBnyQ1iWsGEM4wvmi6RJu4dIUgigu4KS4gkbqCoows2/fUZCTTeyxM4BvSc79O4+spjPoFMQICT0W0TGwzlbYitm2DtpqhcW+jg80pd7GgExmKipijbdclIN7wxjrRNkQAdHwZhhDeIYI91wbIr4du/9AZeveWdQ7WFi/NVERelaPzJUnGtgzY3+yrApKXbe9hzMFdiy5lw3ANS0jMGhgBejxjzDYECrs2IJvGiKrNe1LwIhCV7Z+1lVWmLizkGawIkx38eKqOoLwHNvQXYcod5z1+/2zs+0ThAsrUY5yVBkIRXcR9AQwjXOqjE4ZNm6vxYIF3E8rm8Ch2vOVgJBtO5e1VZZVrSO5K7CqYxsZCMeWbXmwp+lekMkMWFiKA9eIMYR93EAQkcbtP3hoPza2cLYMM8o1jXXdLSOZ4JjOATeAU1P7AIZpA9cNmAxYm63bk5RUcFN3wh24B6u7txOci8qCotiEnbEimMTCk8BBxJqbZGMIz8hIw5NVGxxuW91HhBHBhqzgEY4FtuU8S06vw4qynwqEE1iG3nUd5KYD66SkCj5CiKYOoeCu5EwZloO9PpGTjonnzXVFLxjEEGZwpHHbCx8hg0oejBjRIuJ16BGCW7XspwSxFfxqZh00AULTyScjVBwXBkLIHi4hGK5iE8pjYiVLLbY+saY90CpCl6ys4TErY3cWMYQn4JebfXtXLWBDBncXUNaE3ZT323AmKCSha0MnmLhqIseaOoRgNYJQdAjRehPG9hR0jVWtD+ImGvyaJJzAJEjCcMa3Ss+NPcdI/N6W1wEjQd0KV+3/L4QVIhYAYVeEpWNfBScdQniYZsUhZCBbQN60zqiCZmVQtMAVhVyHYFSFKBOibejPIWBDsj+E2W7jZRrkswhFkjDkpfiWEDsVL5YiQsho3jpkfV4K1tWduwsKK07kZlOe1pWJYzZdVFgiliL7htehvz/MZBDB3nmGIPTZ0CLcjrDhFGcLj9BnQ8WNNGAyLx8iwrFQqdsprIOSvOvCMkGYkaDGUTRzOlXrM90NxSihKANiFhMRUr6L1A93wOAaez5sOWBDmzBiHcpTnw2DkcYlRNlBbBO7skBsyi5hhSAcCyQvFNhQwkNnQTyeDhRS4oyYHsq83iqPsmF529qmcGYgB22Ig+lmREJMJnSDSabTQlW596m9OkRGu9gNEooEIXo2tR50h77p1vxuygGxF2jChIy9m9b3Xk+ECKUYJw0SjiHjO5tc2IY2IQMJERkxw9kfaWis6VzWAadzAi2DCb2wK0/GOKYwDPnyBBIiK0zdDh2KBGHihTG8YUFkAgDsIx/tu0MYREhs28CtoarZ3AunQ4aRIbYAIWfVZnbGtyIeY9vQLtseYVKshO/GZWRNqNvNI+cQWrUt9lJcpaKjNlhHJQxqU5ZnUGyLE87uXw1BG8ve44duHmW+jPtKiRuhsvOcvI2EGgr8K2sIlAObO+cRJsz0UGHlLnqoS9lWzx4HbQ0rqG4tCmm6UmlZnYKsatrEDRwD1JG4gaINNY1ml2DSDNIFLMOZMdB7UtNr4SQV5RErOHMDQSNzB945RC4nI8MzHH8G/e2Gv+ZkRnjI3jmHh0gn6N1GxEZUU6+h/lAQcBzg4Qi1vcJU59HRTIMjEc7ZHc8AxgrQBfbaE7FuOslRnnRxfyh0jTa64xTdg9XUKTIjN4AFhxhFrQ7tsTnTnQfWMQUIsoLR7umzujJz3avc396AKnprCzdE+9vb+4AHP/Q5D7B5tr2HH8IWMeRkFEwvuKF5FFkVqwU158A5ElWY66AlWKdUp6/h2miro956fNTGhrt02491Dav+aIJtxJZmH+L6ljdUhKgo6A88vNbM8UbJ6Apo1GNL9fIIaiCC2jnZH52TrR83ihhyJkdu+sk6qI2FtmecI12X0QaSc6rtrnm5PahNp7WJ3vHCgjRw1UaWnzhHuu0miljXEIuG9jGU+tQxBtfRjel0agzaXnxguPPRaLTtaTQ665/zDDl7huuPiEEja8h3ew3MybLM48bX+xUS48RKzpV1tqyLM+uxGTMBcqpbXqDRZbhbk/NNDl1ZJmTHbn+N6hvEce79liHe0Go8ngLXlDszjVWEQWjQnMktYpylvTqUp9rMSa/wR5pC/TlJvIIyyWNNlMjn21ajbEivylON9TW6md4YtWo0vI1eTE2oJsa+grRtimNqXtQuIOiwFLHnRQooAAQoilZIHCr7cOvOWJupnXHLWB0XReqgzeyu8wYLyvCWQc2r9sVUnrTQi5DpoN3rtAczVRuEa0fKVZ6IogDlKNSkrFjvduZfQZ86xthUFQXq91qPjq+efZtQGOV7qKLvUfGFpWdFi7E3ep71rGf59F/gRpLnslsokAAAAABJRU5ErkJggg==" alt="No carga la imagen">
        </div>

    </div>

  </div>

  <div class="bg-gray-900 py-10">
    <h1 class="text-white text-6xl font-bold text-center py-10">Conectame</h1>
    <div class="flex flex-col text-center">
      <h1 class="text-white py-8 px-10 ">Telefono: 991117845</h1>
      <h1 class="text-white py-8 px-10 ">Correo: omarrojasp1999@gmail.com</h1>
      <h1 class="text-white py-8 px-10">Github 1: https://github.com/maximo261199</h1>
      <h1 class="text-white  py-8 px-10 ">Github 2: https://github.com/OMARROJASP</h1>
    </div>
     
    
  </div>
<div>
  <h1 class="text-gray-600 flex justify-end px-2 py-5">©MaximoOmar2023</h1>
</div>

</template>

<script setup>



</script>