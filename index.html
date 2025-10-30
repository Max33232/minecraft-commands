<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minecraft Commands Generator</title>
  <link rel="icon" href="https://www.minecraft.net/etc.clientlibs/minecraft/clientlibs/main/resources/favicon.ico">
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white min-h-screen flex flex-col items-center justify-start p-4">

  <!-- Верхняя часть -->
  <div class="flex flex-col items-center mt-4">
    <img src="https://www.minecraft.net/etc.clientlibs/minecraft/clientlibs/main/resources/favicon.ico" alt="Minecraft Icon" class="w-16 h-16 mb-2">
    <h1 class="text-2xl font-bold text-green-400">Commands</h1>
  </div>

  <!-- Смайлики в правом верхнем углу -->
  <div class="absolute top-4 right-6 text-2xl">
    😎🔥💣⚔️🐷
  </div>

  <!-- Поле ввода -->
  <div class="mt-10 w-full max-w-lg flex flex-col items-center">
    <textarea id="commandInput"
      maxlength="1000"
      placeholder="Напиши команду, например: 'сделай тнт 3x3'..."
      class="w-full h-32 bg-gray-900 text-white p-3 rounded-xl border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-500 resize-none"></textarea>

    <button id="generateBtn"
      class="mt-4 bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-2 rounded-xl transition">
      Генерировать
    </button>

    <!-- Результат -->
    <div id="output" class="mt-6 w-full bg-gray-800 text-green-400 p-4 rounded-xl font-mono text-sm"></div>
  </div>

  <script>
    const btn = document.getElementById('generateBtn');
    const input = document.getElementById('commandInput');
    const output = document.getElementById('output');

    btn.addEventListener('click', () => {
      const text = input.value.toLowerCase().trim();
      let result = "";

      if (!text) {
        result = "❌ Пожалуйста, введите текст!";
      } else if (text.includes("тнт")) {
        const size = text.match(/\d+/)?.[0] || "1";
        result = `/fill ~-${size} ~ ~-${size} ~${size} ~${size} ~${size} tnt`;
      } else if (text.includes("моб")) {
        result = `/summon minecraft:zombie ~ ~ ~ {Passengers:[{id:"minecraft:skeleton"}]}`;
      } else if (text.includes("жизн")) {
        result = `/effect give @a minecraft:regeneration 99999 255 true`;
      } else if (text.includes("отключи ai")) {
        result = `/summon minecraft:zombie ~ ~ ~ {NoAI:1b}`;
      } else {
        result = `⚙️ Неизвестная команда. Попробуй: "сделай тнт 3x3", "заспавнь моба", "отключи ai моба"`;
      }

      output.textContent = result;
    });
  </script>

</body>
</html>
