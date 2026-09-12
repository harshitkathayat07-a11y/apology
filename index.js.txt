const noButton = document.getElementById('noBtn');
const yesButton = document.getElementById('yesBtn');
const modal = document.getElementById('loveModal');
const closeBtn = document.getElementById('closeBtn');

// Hide the "No" button when touched or clicked
noButton.addEventListener('click', () => {
  noButton.classList.add('hidden');
});

// Show the popup window when "Yes" is clicked
yesButton.addEventListener('click', () => {
  modal.classList.add('active');
});

// Close the popup window when "Close" is clicked
closeBtn.addEventListener('click', () => {
  modal.classList.remove('active');
});