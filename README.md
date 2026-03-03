<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RED HUB | The Ultimate 2026 Omni-Script</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Montserrat:wght@400;900&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #0a0a0a;
            background-image: url('https://www.transparenttextures.com/patterns/carbon-fibre.png');
            font-family: 'Montserrat', sans-serif;
            color: white;
        }
        .neon-text {
            color: #ff0000;
            text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000;
            font-family: 'Anton', sans-serif;
        }
        .neon-border {
            border: 1px solid #ff0000;
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.3);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
            box-shadow: 0 0 25px rgba(255, 0, 0, 0.5);
        }
        .btn-red {
            background: linear-gradient(45deg, #8b0000, #ff0000);
            transition: 0.3s;
        }
        .btn-red:hover {
            letter-spacing: 2px;
            box-shadow: 0 0 20px #ff0000;
        }
    </style>
</head>
<body class="overflow-x-hidden">

    <header class="min-h-screen flex flex-col items-center justify-center text-center px-4">
        <div class="neon-border p-8 md:p-16 bg-black bg-opacity-80 rounded-sm">
            <h1 class="text-6xl md:text-9xl neon-text mb-4 tracking-wider">RED HUB</h1>
            <p class="text-gray-400 text-lg md:text-2xl font-light uppercase tracking-[0.3em] mb-8">
                The Best Omni-Script of 2026
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#features" class="btn-red px-10 py-4 font-black rounded-sm uppercase italic">View Features</a>
                <button onclick="copyScript()" class="border border-white hover:bg-white hover:text-black px-10 py-4 font-black rounded-sm uppercase italic transition">Get Script</button>
            </div>
        </div>
    </header>

    <section id="features" class="py-24 px-8 max-w-7xl mx-auto">
        <h2 class="text-4xl neon-text text-center mb-16 uppercase italic">Dominating the Metaverse</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="feature-card bg-neutral-900 p-8 rounded-sm border-l-4 border-red-600">
                <h3 class="text-2xl font-black mb-4">🌲 99 NIGHTS</h3>
                <ul class="text-gray-400 space-y-2">
                    <li>• 1000 Day AFK (Sky God)</li>
                    <li>• Jitter Anti-Detection</li>
                    <li>• Infinite Hunger/Stamina</li>
                    <li>• Auto-Kill Aura</li>
                </ul>
            </div>

            <div class="feature-card bg-neutral-900 p-8 rounded-sm border-l-4 border-red-600">
                <h3 class="text-2xl font-black mb-4">🧠 BRAINROT</h3>
                <ul class="text-gray-400 space-y-2">
                    <li>• Instant Sigma Collection</li>
                    <li>• Auto-Steal Brains</li>
                    <li>• Skibidi Godmode</li>
                    <li>• Speed-Farm Bypass</li>
                </ul>
            </div>

            <div class="feature-card bg-neutral-900 p-8 rounded-sm border-l-4 border-red-600">
                <h3 class="text-2xl font-black mb-4">⚔️ BLOX FRUITS</h3>
                <ul class="text-gray-400 space-y-2">
                    <li>• Smooth Tween Level Farm</li>
                    <li>• Sea Event Automation</li>
                    <li>• Invisible Attack Mode</li>
                    <li>• Mastery Farm (AFK)</li>
                </ul>
            </div>
        </div>
    </section>

    <footer class="py-12 border-t border-neutral-800 text-center text-gray-600 text-sm">
        <p>&copy; 2026 RED HUB OFFICIAL. NOT AFFILIATED WITH ROBLOX CORP.</p>
        <p class="mt-2 tracking-widest text-red-900 uppercase">Premium Quality Engineering</p>
    </footer>

    <script>
        function copyScript() {
            const script = "loadstring(game:HttpGet('https://raw.githubusercontent.com/YourUsername/RedHub/main/script.lua'))()";
            navigator.clipboard.writeText(script);
            alert("Script copied to clipboard! Paste it into Delta.");
        }
    </script>
</body>
</html>
