<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zufälliger Logo-Generator - Readme</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-300">

    <div class="container mx-auto max-w-4xl px-4 py-12">

        <header class="text-center mb-12">
            <h1 class="text-5xl font-bold text-white mb-4">Zufälliger Logo-Generator</h1>
            <p class="text-xl text-gray-400">
                Ein einfacher, webbasierter Generator zum Erstellen von einzigartigen, organischen Logos im "Blob"-Stil mit transparentem Hintergrund. Perfekt für schnelle Design-Ideen, Platzhalter oder als Inspiration.
            </p>  
        </header>

        <main>
            <!-- Vorschaubereich -->
            <section id="preview" class="mb-16">
                <h2 class="text-3xl font-bold text-white text-center mb-8">Vorschau</h2>
                <div class="bg-gray-800 rounded-xl p-6 shadow-2xl">
                    <p class="text-center text-gray-400 mb-6">
                        Hier sind zwei Beispiele, die mit dem Generator erstellt wurden. Die Form kann über einen Regler von "eckiger" zu "runder" angepasst werden.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-center">
                        <!-- Eckigeres Beispiel -->
                        <div class="bg-gray-700 rounded-lg p-4 flex flex-col">
                            <h3 class="text-lg font-semibold text-white mb-2">Eckigere Form</h3>
                            <div class="flex-grow flex items-center justify-center bg-white rounded-md">
                               <img src="https://github.com/WildCooding/raondom-logo-generator/blob/main/Example01.png?raw=true" alt="Beispiel eines eckigeren Logos" class="rounded-md max-w-full max-h-full">
                            </div>
                        </div>
                        <!-- Runderes Beispiel -->
                        <div class="bg-gray-700 rounded-lg p-4 flex flex-col">
                            <h3 class="text-lg font-semibold text-white mb-2">Rundere Form</h3>
                            <div class="flex-grow flex items-center justify-center bg-white rounded-md">
                                <img src="https://github.com/WildCooding/raondom-logo-generator/blob/main/Example02.png?raw=true" alt="Beispiel eines runderen Logos" class="rounded-md max-w-full max-h-full">
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Feature-Bereich -->
            <section id="features" class="mb-16">
                <h2 class="text-3xl font-bold text-white text-center mb-8">✨ Features</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">Zufällige Formen & Farben</h3>
                        <p class="text-gray-400">Erstelle mit einem Klick ein komplett neues Logo mit einem zufälligen Farbverlauf und einer organischen Form.</p>
                    </div>
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">Anpassbare Rundung</h3>
                        <p class="text-gray-400">Verwende den Schieberegler, um die Form stufenlos von spitzer und unregelmäßiger zu weich und rund zu ändern.</p>
                    </div>
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">SVG-Download</h3>
                        <p class="text-gray-400">Lade das erstellte Logo als Vektordatei (.svg) herunter. Vektoren sind unendlich skalierbar, ohne an Qualität zu verlieren.</p>
                    </div>
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">PNG-Download</h3>
                        <p class="text-gray-400">Exportiere das Logo als PNG-Datei mit transparentem Hintergrund in verschiedenen gängigen Auflösungen (z.B. 128px, 512px, 2048px).</p>
                    </div>
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg md:col-span-2">
                        <h3 class="text-xl font-bold text-white mb-2">Keine Installation nötig</h3>
                        <p class="text-gray-400">Läuft direkt im Browser. Das gesamte Tool ist in einer einzigen HTML-Datei enthalten.</p>
                    </div>
                </div>
            </section>

            <!-- Anleitungs-Bereich -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <section id="usage">
                    <h2 class="text-3xl font-bold text-white mb-6">🚀 Benutzung</h2>
                    <ol class="list-decimal list-inside space-y-4 text-lg">
                        <li><strong>Öffne die `index.html`-Datei</strong> in deinem bevorzugten Webbrowser.</li>
                        <li>Klicke auf den Button <strong>"Neues Logo generieren"</strong>, um ein zufälliges Logo zu erstellen.</li>
                        <li>Passe die Form mit dem <strong>"Rundung"</strong>-Schieberegler an deine Wünsche an.</li>
                        <li>Klicke auf <strong>"Als SVG herunterladen"</strong> oder <strong>"Als PNG herunterladen"</strong>, um dein fertiges Logo zu speichern.</li>
                    </ol>
                </section>

                <section id="local-dev">
                    <h2 class="text-3xl font-bold text-white mb-6">💻 Lokal ausführen</h2>
                    <div class="space-y-4">
                        <div>
                            <h3 class="font-semibold text-white">1. Klone das Repository:</h3>
                            <pre class="bg-gray-950 rounded-md p-4 mt-2 text-sm text-gray-300 overflow-x-auto"><code>git clone https://github.com/WildCooding/raondom-logo-generator.git</code></pre>
                        </div>
                        <div>
                            <h3 class="font-semibold text-white">2. Navigiere in den Ordner:</h3>
                            <pre class="bg-gray-950 rounded-md p-4 mt-2 text-sm text-gray-300 overflow-x-auto"><code>cd raondom-logo-generator</code></pre>
                        </div>
                        <div>
                           <h3 class="font-semibold text-white">3. Öffne die `index.html`:</h3>
                           <p class="text-gray-400 mt-2">Öffne die Datei direkt in deinem Browser (z.B. per Doppelklick).</p>
                        </div>
                    </div>
                </section>
            </div>
        </main>
        
        <footer class="text-center mt-16 pt-8 border-t border-gray-700">
            <p class="text-gray-500">Das ist alles! Viel Spaß beim Erstellen deiner Logos.</p>
        </footer>

    </div>
</body>
</html>
