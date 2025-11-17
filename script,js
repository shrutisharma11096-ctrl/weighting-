// Small helper script for the demo contact form and date
document.getElementById('year').textContent = new Date().getFullYear();

function submitForm(e){
  e.preventDefault();
  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const message = document.getElementById('message').value.trim();
  const status = document.getElementById('formStatus');

  if(!name || !email || !message){
    status.textContent = 'Please fill all fields.';
    return;
  }

  // This demo does not send real emails.
  // For production, connect to an API or use Formspree / Netlify Forms / GitHub Actions.
  status.textContent = 'Thanks — your message is received (demo).';
  status.style.color = 'green';

  // clear form
  document.getElementById('contactForm').reset();
}
