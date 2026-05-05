function scrollToSection(id) {
  document.getElementById(id).scrollIntoView({
    behavior: "smooth"
  });
}

function mostrarInfo(id) {
  document.querySelectorAll('.info').forEach(el => el.classList.add('hidden'));
  document.getElementById(id).classList.remove('hidden');
}
