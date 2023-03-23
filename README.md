<h1 align="left">Hi 👋, I'm Praveen Shekar</h1>
<h3 align="left">A passionate Data Analytics and Machine Learning enthusiast from India</h3>

- 💬 Ask me about **Python, Excel, MySQL**

- 📫 How to reach me **s.praveen795@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<div class="repos">
  <h2>Active Repositories</h2>
  <ul id="repo-list"></ul>
</div>

<script>
  fetch('https://api.github.com/users/X1raven/repos')
    .then(response => response.json())
    .then(data => {
      const repos = document.getElementById('repo-list');
      data.forEach(repo => {
        const li = document.createElement('li');
        li.innerHTML = `<a href="${repo.html_url}">${repo.name}</a>`;
        repos.appendChild(li);
      });
    });
</script>
