# <div id="typewriter"></div>

A passionate Frontend Developer from España

🔭 I’m currently working on **NexTret - IT ServiceDesk L1/ L2**

🌱 I’m currently learning **MongoDB and Typescript**

👯 I’m looking to collaborate on **Frontend & Backend**

👨‍💻 All of my projects are available at [My Portfolio](https://diego-monfort-landolt.github.io/Landoltdiego)

💬 Ask me about **React, Vite, Typescript, JavaScript, HTML, and CSS**

## Languages and Tools:

<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <img src="angular.png" alt="Angular" style="width: 50px; height: 50px; margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); animation: bounce 2s infinite;">
  <img src="aws.png" alt="AWS" style="width: 50px; height: 50px; margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); animation: bounce 2s infinite;">
  <img src="azure.png" alt="Azure" style="width: 50px; height: 50px; margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); animation: bounce 2s infinite;">
  <!-- Füge hier weitere Icons hinzu -->
</div>

<style>
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-10px);
  }
  60% {
    transform: translateY(-5px);
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

#typewriter {
  font-size: 2em;
  font-weight: bold;
  white-space: nowrap;
  overflow: hidden;
  border-right: 0.15em solid black;
  animation: typing 3.5s steps(40, end), blink 0.75s step-end infinite;
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
  const typewriter = document.getElementById('typewriter');
  const text = "Hi 👋, I'm Diego";
  let index = 0;

  function type() {
    if (index < text.length) {
      typewriter.innerHTML += text.charAt(index);
      index++;
      setTimeout(type, 100);
    } else {
      setTimeout(() => {
        typewriter.innerHTML = "";
        index = 0;
        type();
      }, 2000);
    }
  }

  type();
});
</script>

