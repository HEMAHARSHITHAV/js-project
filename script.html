const menuBtn = document.getElementById("menuBtn");
const navbar = document.getElementById("navbar");

// Mobile navigation menu
menuBtn.addEventListener("click", () => {
  const isOpen = navbar.classList.toggle("open");

  menuBtn.textContent = isOpen ? "✕" : "☰";
  menuBtn.setAttribute("aria-expanded", String(isOpen));
});

// Close menu after clicking a navigation link
navbar.querySelectorAll("a").forEach((link) => {
  link.addEventListener("click", () => {
    navbar.classList.remove("open");
    menuBtn.textContent = "☰";
    menuBtn.setAttribute("aria-expanded", "false");
  });
});

// Animated job title
const words = [
  "Aspiring Web Developer",
  "Computer Science Student",
  "Creative Problem Solver"
];

let wordIndex = 0;
let charIndex = 0;
let deleting = false;

const typing = document.getElementById("typing");

function typeEffect() {
  const currentWord = words[wordIndex];

  typing.textContent = currentWord.substring(0, charIndex);

  if (!deleting && charIndex < currentWord.length) {
    charIndex++;
    setTimeout(typeEffect, 85);
  } else if (!deleting) {
    deleting = true;
    setTimeout(typeEffect, 1200);
  } else if (charIndex > 0) {
    charIndex--;
    setTimeout(typeEffect, 40);
  } else {
    deleting = false;
    wordIndex = (wordIndex + 1) % words.length;
    setTimeout(typeEffect, 250);
  }
}

typeEffect();

// Contact form: prepare an email
const contactForm = document.getElementById("contactForm");

contactForm.addEventListener("submit", (event) => {
  event.preventDefault();

  const name = document.getElementById("name").value.trim();
  const email = document.getElementById("email").value.trim();
  const message = document.getElementById("message").value.trim();
  const status = document.getElementById("formStatus");

  if (!name || !email || !message) {
    status.textContent = "Please complete all fields.";
    return;
  }

  const subject = encodeURIComponent(
    "Portfolio message from " + name
  );

  const body = encodeURIComponent(
    "Name: " + name +
    "\nEmail: " + email +
    "\n\nMessage:\n" + message
  );

  status.textContent = "Opening your email application...";

  window.location.href =
    "mailto:hemaharshithav05@gmail.com" +
    "?subject=" + subject +
    "&body=" + body;
});

// Automatically display the current year
document.getElementById("year").textContent =
  new Date().getFullYear();
