// Grab elements
const claimBtn = document.getElementById('claim-btn');
const promoScreen = document.getElementById('promo-screen');
const prankScreen = document.getElementById('prank-screen');
const showBioBtn = document.getElementById('show-bio-btn');
const bioPopup = document.getElementById('bio-popup');
const closeBioBtn = document.getElementById('close-bio-btn');

// When user clicks “Claim Offer Now”
claimBtn.addEventListener('click', () => {
  // hide promo, show prank
  promoScreen.classList.add('hidden');
  prankScreen.classList.remove('hidden');
});

// Show bio popup
showBioBtn.addEventListener('click', () => {
  bioPopup.classList.remove('hidden');
});

// Close bio popup
closeBioBtn.addEventListener('click', () => {
  bioPopup.classList.add('hidden');
});