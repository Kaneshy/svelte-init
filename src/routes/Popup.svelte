<!-- Popup.svelte -->

<script>
    export let isOpen = false;
  
    function togglePopup() {
      isOpen = !isOpen;
    }
  </script>
  
  {#if isOpen}
    <div class="popup">
      <!-- Contenido del popup aquí -->
      <p>¡Hola! Este es el contenido del popup.</p>
      <img width="250" src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1704496776/FASHION/Bags___Accessories_Hats_Scarves___Gloves_Mega_Menu_Espots_M_jznuam.jpg" alt="">
    </div>
  {/if}
  
  <button on:click={togglePopup}>Mostrar Popup</button>
  
  <style>
    .popup {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background-color: white;
      padding: 20px;
      border: 1px solid #ccc;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      z-index: 999;
    }
  </style>
  