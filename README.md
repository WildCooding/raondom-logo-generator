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
        .feature-icon {
            width: 28px;
            height: 28px;
            stroke-width: 1.5;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-300">

    <div class="container mx-auto max-w-4xl px-4 py-12">

        <header class="text-center mb-12">
            <h1 class="text-5xl font-bold text-white mb-4">Zufälliger Logo-Generator</h1>
            <p class="text-xl text-gray-400">
                Ein einfacher, webbasierter Generator zum Erstellen von einzigartigen, organischen Logos im "Blob"-Stil.
            </p>
        </header>

        <main>
            <!-- Vorschaubereich -->
            <section id="preview" class="mb-16">
                <h2 class="text-3xl font-bold text-white text-center mb-8">Vorschau</h2>
                <div class="bg-gray-800 rounded-xl p-6 shadow-2xl">
                    <p class="text-center text-gray-400 mb-6">
                        Die Form kann über einen Regler von "eckiger" zu "runder" angepasst werden.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-center">
                        <!-- Eckigeres Beispiel -->
                        <div class="bg-gray-700 rounded-lg p-4">
                            <h3 class="text-lg font-semibold text-white mb-2">Eckigere Form</h3>
                            <img src="https://placehold.co/400x400/f97316/FFFFFF?text=Eckiges+Logo" alt="Beispiel eines eckigeren Logos" class="rounded-md w-full aspect-square object-cover">
                        </div>
                        <!-- Runderes Beispiel -->
                        <div class="bg-gray-700 rounded-lg p-4">
                            <h3 class="text-lg font-semibold text-white mb-2">Rundere Form</h3>
                             <img src="https://placehold.co/400x400/3b82f6/FFFFFF?text=Rundes+Logo" alt="Beispiel eines runderen Logos" class="rounded-md w-full aspect-square object-cover">
                        </div>
                    </div>
                </div>
            </section>

            <!-- Feature-Bereich -->
            <section id="features" class="mb-16">
                <h2 class="text-3xl font-bold text-white text-center mb-8">✨ Features</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Feature 1 -->
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">Zufällige Formen & Farben</h3>
                        <p class="text-gray-400">Erstelle mit einem Klick ein komplett neues Logo mit zufälligem Farbverlauf und organischer Form.</p>
                    </div>
                    <!-- Feature 2 -->
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">Anpassbare Rundung</h3>
                        <p class="text-gray-400">Verwende den Schieberegler, um die Form stufenlos von spitzer zu weicher zu ändern.</p>
                    </div>
                    <!-- Feature 3 -->
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">SVG-Download</h3>
                        <p class="text-gray-400">Lade das Logo als unendlich skalierbare Vektordatei (.svg) herunter.</p>
                    </div>
                    <!-- Feature 4 -->
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg">
                        <h3 class="text-xl font-bold text-white mb-2">PNG-Download</h3>
                        <p class="text-gray-400">Exportiere das Logo als PNG mit transparentem Hintergrund in verschiedenen Auflösungen.</p>
                    </div>
                    <!-- Feature 5 -->
                    <div class="bg-gray-800 rounded-xl p-6 shadow-lg col-span-1 md:col-span-2 lg:col-span-1">
                        <h3 class="text-xl font-bold text-white mb-2">Keine Installation</h3>
                        <p class="text-gray-400">Läuft direkt im Browser. Das gesamte Tool ist in einer einzigen HTML-Datei enthalten.</p>
                    </div>
                </div>
            </section>

            <!-- Anleitungs-Bereich -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <section id="usage">
                    <h2 class="text-3xl font-bold text-white mb-6">🚀 Benutzung</h2>
                    <ol class="list-decimal list-inside space-y-4 text-lg">
                        <li>Öffne die `index.html`-Datei in deinem bevorzugten Webbrowser.</li>
                        <li>Klicke auf **"Neues Logo generieren"**, um ein zufälliges Logo zu erstellen.</li>
                        <li>Passe die Form mit dem **"Rundung"**-Schieberegler an deine Wünsche an.</li>
                        <li>Klicke auf **"Als SVG herunterladen"** oder **"Als PNG herunterladen"**, um dein Logo zu speichern.</li>
                    </ol>
                </section>

                <section id="local-dev">
                    <h2 class="text-3xl font-bold text-white mb-6">💻 Lokal ausführen</h2>
                    <div class="space-y-4">
                        <div>
                            <h3 class="font-semibold text-white">1. Klone das Repository:</h3>
                            <pre class="bg-gray-950 rounded-md p-4 mt-2 text-sm text-gray-300 overflow-x-auto"><code>git clone https://github.com/DEIN_BENUTZERNAME/DEIN_REPO_NAME.git</code></pre>
                        </div>
                        <div>
                            <h3 class="font-semibold text-white">2. Navigiere in den Ordner:</h3>
                            <pre class="bg-gray-950 rounded-md p-4 mt-2 text-sm text-gray-300 overflow-x-auto"><code>cd DEIN_REPO_NAME</code></pre>
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
            <p class="text-gray-500">Viel Spaß beim Erstellen deiner Logos!</p>
        </footer>

    </div>
</body>
</html>
