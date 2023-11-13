# Mejorando mi Lógica de Programación en Exercism

## ¿Cómo Empezar?

1. Clona este repositorio con un clic: [![Clone](https://img.shields.io/badge/Clone-Click%20to%20Copy-blue?style=flat-square)](<javascript:void(0)>)

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const cloneButton = document.querySelector('.clone-button');
    cloneButton.addEventListener('click', function() {
      const repoURL = 'https://github.com/tu-usuario/tu-repositorio.git';  // Reemplaza con tu URL
      const tempInput = document.createElement('input');
      tempInput.value = `git clone ${repoURL}`;
      document.body.appendChild(tempInput);
      tempInput.select();
      document.execCommand('copy');
      document.body.removeChild(tempInput);
      alert('¡Comando copiado al portapapeles!');
    });
  });
</script>
