<div align="center">

# Frontend Developer 🚀

<img  alt="ChatGPT Image May 21, 2026, 12_17_57 PM" src="https://github.com/user-attachments/assets/1b112e6e-cb47-492a-a02c-4cb73c9f17dd" />
<div class="skills-wrapper">

  <div class="skill">HTML5</div>
  <div class="skill">CSS3</div>
  <div class="skill">JavaScript</div>
  <div class="skill">React</div>
  <div class="skill">Tailwind CSS</div>

</div>

<style>
.skills-wrapper {
  display: flex;
  flex-direction: column;
  gap: 12px;
  align-items: flex-start;
}

.skill {
  padding: 10px 18px;
  background: linear-gradient(90deg, #00c6ff, #0072ff);
  color: white;
  border-radius: 8px;
  font-weight: bold;

  transform: translateX(-100%);
  opacity: 0;
  animation: slideIn 1s forwards;
}

/* one by one delay */
.skill:nth-child(1) { animation-delay: 0.2s; }
.skill:nth-child(2) { animation-delay: 0.6s; }
.skill:nth-child(3) { animation-delay: 1s; }
.skill:nth-child(4) { animation-delay: 1.4s; }
.skill:nth-child(5) { animation-delay: 1.8s; }

@keyframes slideIn {
  to {
    transform: translateX(0);
    opacity: 1;
  }
}
</style>

</div>
