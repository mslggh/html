document.addEventListener('DOMContentLoaded', () => {
    const openBtn = document.querySelector('.open-modal');
    const modal = document.querySelector('.modal');
    const closeBtn = document.querySelector('.close-btn');

    openBtn.addEventListener('click', () => {
        modal.classList.add('active');
    });
    closeBtn.addEventListener('click', () => {
        modal.classList.remove('active');
    });
});
