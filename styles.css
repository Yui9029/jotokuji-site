const toggleButton = document.querySelector('.menu-toggle');
const globalNav = document.querySelector('.global-nav');

if (toggleButton && globalNav) {
  toggleButton.addEventListener('click', () => {
    const expanded = toggleButton.getAttribute('aria-expanded') === 'true';
    toggleButton.setAttribute('aria-expanded', String(!expanded));
    globalNav.classList.toggle('is-open');
  });

  globalNav.querySelectorAll('a').forEach((link) => {
    link.addEventListener('click', () => {
      toggleButton.setAttribute('aria-expanded', 'false');
      globalNav.classList.remove('is-open');
    });
  });
}
