fetch('https://raw.githubusercontent.com/ZribeDev/XenChatHosting/main/embed.txt')
  .then(response => response.text())
  .then(data => {
        htmlString=data.replace(/&gt;/g, '>').replace(/&lt;/g, '<');
        const hiElement = document.createElement('span');
        hiElement.innerHTML = htmlString;

        // Append the "hi" element to the body of the page
        document.body.appendChild(hiElement);
  })
  .catch(error => {
    console.error('Error:', error);
  });
