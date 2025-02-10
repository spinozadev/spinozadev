
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.7 user-scalable=no" />
    <meta property="og:title" content="Spinoza">
    <meta property="og:image" content="https://spinoza.wtf/img/spinoza.png">
    <meta property="og:site_name" content="spinoza.wtf">
    <meta property="og:description" content="root@spinoza:~$">
    <title> { spinoza.wtf } </title>
    <link rel="stylesheet" href="https://spinoza.wtf/fonts/inter.css">
    <link rel="stylesheet" href="https://spinoza.wtf/npm/@spinoza/style/style.css">
    <link rel="icon" type="image/x-icon" href="https://spinoza.wtf/favicon.ico">
    <style>
        @import url("https://fonts.xz.style/serve/fira-code.css");

        :root {
            --nc-font-sans: 'Fira Code', monospace;
            --nc-font-mono: 'Fira Code', monospace;
            --nc-tx-1: #FFFFFF;
            --nc-tx-2: #DDDDDD;
            --nc-bg-1: #111111;
            --nc-bg-2: #0A0A0A;
            --nc-bg-3: #000000;
            --nc-lk-1: #4A90E2;
            --nc-lk-2: #E2E2E2;
            --nc-lk-tx: #FFFFFF;
            --nc-ac-1: #FF7F50;
            --nc-ac-tx: #FFFFFF;
        }

        op {
            opacity: 0.3;
            text-shadow: 0px 0px 5px rgba(161, 161, 161, 0.7);
        }

        shadow {
            color: #ffffff;
            text-shadow: 0px 0px 3px rgba(255, 255, 255, 0.7);
        }

        a {
            text-decoration: none;
        }

        td strong a {
            text-decoration: none;
        }

        body {
            user-select: none;
        }

        body::-webkit-scrollbar {
            display: none;
        }

        body {
            scrollbar-width: none;
            -ms-overflow-style: none;
        }
        

        header {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            padding-bottom: 5px !important;
        }

        .platform-logo {
            width: 20px;
            height: auto;
            margin-right: 5px;
        }

        .typing-effect {
            display: inline-block;
            white-space: nowrap;
            overflow: hidden;
            animation: typing 1.5s steps(20, end), blink-caret 0.5s step-end infinite;
        }

        @keyframes typing {
            from {
                width: 0
            }

            to {
                width: 100%
            }
        }

        @keyframes blink-caret {
            from,
            to {
                border-color: transparent
            }

            50% {
                border-color: #000
            }
        }

        ::-webkit-scrollbar {
            display: none;
        }

        html {
            scrollbar-width: none;
        }

           
    .python {
        color: #4B8BBE;
        text-shadow: 0px 0px 2px #4B8BBE;
    }

    .csharp {
        color: #178600;
        text-shadow: 0px 0px 2px #178600;
    }

    .cplusplus {
        color: #F34B7D;
        text-shadow: 0px 0px 2px #F34B7D;;
    }

    .java {
        color: #e86f00;
        text-shadow: 0px 0px 2px #913721;
    }

    .javascript {
        color: #F7DF1E;
        text-shadow: 0px 0px 2px #F7DF1E;

    }
    
    blockquote {
        opacity: 0.9;
        border-radius: 15px; 
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2); 
        backdrop-filter: blur(5px); 
    }

    .contact-section {
        transition: opacity 0.5s ease-in-out, filter 0.5s ease;
        filter: blur(0);
        opacity: 1;
    }

    .contact-section.hidden {
        opacity: 0;
        filter: blur(5px);
        display: none;
    }

    .platform-cell {
        padding-top: 0px;
        padding-bottom: 0px;
    }

    @keyframes blink {
    50% {
        border-color: transparent;
    }
    }

    .hellofriend {
        font-family: 'Courier New', Courier, monospace;
        border-right: 2px solid black;
        white-space: nowrap;
        overflow: hidden;
    }

    .page-indicator {
        font-weight: bold;
        position: absolute;
        right: 0px; 
        top: 50%; 
        transform: translateY(-50%); 
    }

    </style>
</head>

<body>
    <header style="padding-bottom: 10px !important">
        <h1>{ <span id="typingEffect"></span> }</h1>
        <nav>
            <p id="hellofriendEffect"></p>
        </nav>
    </header>

    <div>
        <blockquote>    
            <span id="spinozaText" class="typeing"></span>
        </blockquote>
    </div>

<div id="contactSection1">
    <blockquote>
        <h4 style="padding-bottom: 10px; position: relative;">Contact Me<span class="page-indicator">(1/2)</span>:</h4>
        <table>
            <tr>
                <td style="border: 1px solid #E2E2E2"><strong>Type</strong></td>
                <td style="border: 1px solid #E2E2E2"><strong>Username</strong></td>
                <td class="platform-cell" style="border: 1px solid #E2E2E2 "><strong>Platform</strong></td>
            </tr>
            <tr>
                <td style="position: relative; top: 3px;">User Profile</td>
                <td>
                    <a href="https://discord.com/users/119788257859993601" rel="noreferrer" target="_blank" style="position: relative; top: 3px;">spinoza</a>
                </td>
                <td><img src="https://spinoza.wtf/img/discord.png" class="platform-logo" style="position: relative; top: 4px; margin-right: 1px;"> Discord</td>
            </tr>
            <tr>
                <td style="position: relative; top: 3px;">Mail Address</td>
                <td>
                    <a href="/cdn-cgi/l/email-protection#caa9a5a4beaba9be8ab9baa3a4a5b0abe4bdbeac" style="position: relative; top: 3px;">contact</a>
                </td>
                <td><img src="https://spinoza.wtf/img/email.png" class="platform-logo" style="position: relative; top: 4px; margin-right: 1px;"> E-mail</td>
            </tr>
        </table>
    </blockquote>
</div>

<div id="contactSection2" style="display: none;">
    <blockquote>
        <h4 style="padding-bottom: 10px; position: relative;">Contact Me<span class="page-indicator">(2/2)</span>:</h4>
        <table>
            <tr>
                <td style="border: 1px solid #E2E2E2"><strong>Type</strong></td>
                <td style="border: 1px solid #E2E2E2"><strong>Username</strong></td>
                <td class="platform-cell" style="border: 1px solid #E2E2E2"><strong>Platform</strong></td>
            </tr>
            <tr>
                <td style="position: relative; top: 3px;">User Profile</td>
                <td>
                    <a href="https://instagram.com/spinozapy" rel="noreferrer" target="_blank" style="position: relative; top: 3px;">spinozapy</a>
                </td>
                <td><img src="https://spinoza.wtf/img/instagram.png" class="platform-logo" style="position: relative; top: 4px; margin-right: 1px;"> Instagram</td>
            </tr>
            <tr>
                <td style="position: relative; top: 3px;">User Profile</td>
                <td>
                    <a href="https://github.com/spinozapy" rel="noreferrer" target="_blank" style="position: relative; top: 3px;">spinozapy</a>
                </td>
                <td><img src="https://spinoza.wtf/img/github.png" class="platform-logo" style="position: relative; top: 4px; margin-right: 1px;"> GitHub</td>
            </tr>
        </table>
    </blockquote>
</div>

    <span style="color: gray; font-size: 17px; display: block; text-align: center; margin: 5; padding: 5;">
        ~ Most things have both good and bad; find the balance and act wisely. ~
    </span>


<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
const typingElement = document.getElementById("typingEffect");
const titleElement = document.querySelector("title");
const languages = ["py", "cs", "cpp", "java", "js"];
const languageColors = {
    py: "#4B8BBE",
    cs: "#178600",
    cpp: "#F34B7D",
    java: "#e86f00",
    js: "#F7DF1E"
};
let index = 0;

function typeText() {
    if (index < languages.length) {
        const currentText = languages[index];
        const newText = `${currentText}`;

        typingElement.innerHTML = `spinoza.<span style="color: ${languageColors[currentText]}">${newText}</span>`;
        titleElement.innerText = `{ spinoza.wtf }`; -

        index++;
        setTimeout(() => {
            typeText();
        }, 555);
    } else {
        index = 0;
        setTimeout(() => {
            typeText();
        }, 555);
    }
}

setTimeout(() => {
    typeText();
}, 555);

        document.addEventListener('keydown', function(e) {
            if (e.ctrlKey && (e.key === 'u' || e.key === 'U')) {
                e.preventDefault();
                window.location.href = 'https://spinoza.wtf/bluescreen';
            }
        });
        
        document.addEventListener('keydown', function(e) {
            if (e.key === 'F12') {
                e.preventDefault();
                window.location.href = 'https://spinoza.wtf/redscreen';
            }
        });

        let devToolsOpen = false;
        let devToolsTimer;
        
        function checkDevTools() {
            devToolsOpen = window.outerWidth - window.innerWidth > 200 || window.outerHeight - window.innerHeight > 200;
            if (devToolsOpen) {
                clearInterval(devToolsTimer);
                window.location.href = 'https://spinoza.wtf/redscreen'; 
            }
        }
        
        devToolsTimer = setInterval(checkDevTools, 0); 

    </script>

<script>

document.addEventListener('DOMContentLoaded', function() {
    const element = document.getElementById('hellofriendEffect');
    const text = "Hello friend, I'm Spinoza";
    let index = 0;
    
    function typeWriter(text, callback) {
        if (index < text.length) {
            element.innerHTML += text.charAt(index);
            index++;
            setTimeout(() => typeWriter(text, callback), 77);
        } else if (callback) {
            setTimeout(callback, 200);
        }
    }

    setTimeout(() => {
        typeWriter(text, startSpinozaText);
    }, 777); 

    function startSpinozaText() {
        var data = [
          {
            spinozaText: `<span><h4 style="padding-bottom: 10px;">Who am I?</h4>
              <i><span>I am a <op>malware</op> and <shadow>goodware</shadow> developer.<br/><br/>I have skills in languages:</span><br/><span class="python">Python</span>, <span class="csharp">C#</span>, <span class="cplusplus">C++</span>, <span class="java">Java</span> and <span class="javascript">JavaScript</span>. </i></span>`
          }
        ];

        var allElements = document.getElementsByClassName("typeing");
        for (var j = 0; j < allElements.length; j++) {
          var currentElementId = allElements[j].id;
          var currentElementIdContent = data[0][currentElementId];
          var element = document.getElementById(currentElementId);
          var devTypeText = currentElementIdContent;

          var i = 0, isTag, text;
          (function type() {
            text = devTypeText.slice(0, ++i);
            if (text === devTypeText) {
                setTimeout(() => {
                    document.getElementById("contactMeSection").style.display = "block";
                }, 77); 
                return;
            }
            element.innerHTML = text + `<span class='blinker'>&#32;</span>`;
            var char = text.slice(-1);
            if (char === "<") isTag = true;
            if (char === ">") isTag = false;
            if (isTag) return type();
            setTimeout(type, 60);
          })();
        }
    }
});
        document.addEventListener('DOMContentLoaded', (event) => {
            let keys = ['w', 'w', 's', 's', 'a', 'd', 'a', 'd', 'b', 'a'];
            let userInput = [];

            document.addEventListener('keydown', function(e) {
                const key = e.key.toLowerCase();
                userInput.push(key);
                if (userInput.length > keys.length) {
                    userInput.shift();
                }
                if (userInput.join('') === keys.join('')) {
                    window.location.href = 'https://spinoza.wtf/konami';
                }
            });
        });

        document.addEventListener('DOMContentLoaded', (event) => {
            let keys = ['l', 'e', 'a', 'k'];
            let userInput = [];

            document.addEventListener('keydown', function(e) {
                const key = e.key.toLowerCase();
                userInput.push(key);
                if (userInput.length > keys.length) {
                    userInput.shift();
                }
                if (userInput.join('') === keys.join('')) {
                    window.open('https://leak.run', '_blank');
                }
            });
        });

        document.addEventListener('DOMContentLoaded', (event) => {
            let keys = ['p', 'r', 'e', 'd', 'y'];
            let userInput = [];

            document.addEventListener('keydown', function(e) {
                const key = e.key.toLowerCase();
                userInput.push(key);
                if (userInput.length > keys.length) {
                    userInput.shift();
                }
                if (userInput.join('') === keys.join('')) {
                    window.open('https://predy.fun', '_blank');
                }
            });
        });

        document.addEventListener('DOMContentLoaded', (event) => {
            let keys = ['s', 'w', 'e', 'e', 't'];
            let userInput = [];

            document.addEventListener('keydown', function(e) {
                const key = e.key.toLowerCase();
                userInput.push(key);
                if (userInput.length > keys.length) {
                    userInput.shift();
                }
                if (userInput.join('') === keys.join('')) {
                    window.location.href = 'https://spinoza.wtf/sweet-bonanza';
                }
            });
        });

        document.addEventListener('DOMContentLoaded', (event) => {
            let keys = ['l', 'a', 'i', 'n'];
            let userInput = [];

            document.addEventListener('keydown', function(e) {
                const key = e.key.toLowerCase();
                userInput.push(key);
                if (userInput.length > keys.length) {
                    userInput.shift();
                }
                if (userInput.join('') === keys.join('')) {
                    window.location.href = 'https://spinoza.wtf/lain';
                }
            });
        });

    document.addEventListener('DOMContentLoaded', function() {
    const section1 = document.getElementById('contactSection1');
    const section2 = document.getElementById('contactSection2');

    setInterval(toggleContactSections, 5000);

    function toggleContactSections() {
        if (section1.style.display === 'none') {
            section1.style.display = 'block';
            section2.style.display = 'none';
        } else {
            section1.style.display = 'none';
            section2.style.display = 'block';
        }
    }
});

    </script>
</body>
</html>
