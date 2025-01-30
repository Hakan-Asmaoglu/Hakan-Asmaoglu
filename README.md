<h1 align="center" class="animated-title">Hi, I'm Hakan 👋</h1>

<p align="center" class="animated-tagline">
  <strong>UX Designer | Hobbyist Developer | Communication Specialist</strong>
</p>

<style>
.animated-title {
  animation: fadeInUp 1s ease-in-out; /* Adjust duration and easing */
}

.animated-tagline {
  animation: fadeIn 1.5s ease-in-out; /* Adjust duration and easing */
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Optional: Add a hover effect to the title */
.animated-title:hover {
  transform: scale(1.05); /* Slightly enlarge on hover */
  transition: transform 0.3s ease; /* Smooth transition */
}
</style>
