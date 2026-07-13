<!DOCTYPE html>
<html lang="zh-TW" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IACD 生命能量診斷與人格定位系統</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Noto+Sans+TC:wght@300;400;500;700&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'Noto Sans TC', 'sans-serif'],
          },
          colors: {
            slate: {
              950: '#0B0F19',
            },
          }
        }
      }
    }
  </script>
  <style>
    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #0B0F19;
    }
    ::-webkit-scrollbar-thumb {
      background: #1F2937;
      border-radius: 3px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #374151;
    }
    /* Glow effects */
    .glow-purple {
      box-shadow: 0 0 20px rgba(139, 92, 246, 0.15);
    }
    .glow-teal {
      box-shadow: 0 0 20px rgba(20, 184, 166, 0.15);
    }
    /* Scale animation */
    .transition-all-300 {
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
  </style>
</head>
<body class="bg-slate-950 text-gray-100 min-h-screen font-sans selection:bg-purple-500 selection:text-white">

  <!-- Floating Nav -->
  <nav class="sticky top-0 z-40 bg-slate-950/80 backdrop-blur-md border-b border-gray-800/60 px-4 py-3">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <span class="text-xl font-bold bg-gradient-to-r from-purple-400 via-indigo-400 to-teal-400 bg-clip-text text-transparent">IACD</span>
        <span class="text-xs text-gray-400 border border-gray-800 px-2 py-0.5 rounded-full hidden sm:inline">生命狀態診斷系統</span>
      </div>
      <div class="flex items-center space-x-3">
        <button id="reset-app-btn" class="text-xs text-gray-400 hover:text-white bg-gray-900 border border-gray-800 hover:border-gray-700 px-3 py-1.5 rounded-lg transition" onclick="resetDiagnostics()">
          重置測驗
        </button>
      </div>
    </div>
  </nav>

  <!-- Notification Banner -->
  <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-10 opacity-0 pointer-events-none transition-all duration-300 bg-gray-900 border border-gray-800 text-gray-200 px-4 py-3 rounded-xl shadow-xl flex items-center space-x-2">
    <span id="toast-msg">提示訊息</span>
  </div>

  <main class="max-w-4xl mx-auto px-4 py-8 pb-24">

    <!-- Screen 1: Welcome Screen -->
    <section id="welcome-screen" class="space-y-10 py-6">
      <div class="text-center space-y-4">
        <div class="inline-flex items-center space-x-2 bg-purple-950/40 border border-purple-800/50 text-purple-300 px-3 py-1 rounded-full text-xs font-medium tracking-wide">
          <span>💫 不是性格測試，而是當下能量診斷</span>
        </div>
        <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-none text-white">
          IACD 生命狀態診斷與<br class="hidden sm:inline">
          <span class="bg-gradient-to-r from-purple-400 via-indigo-400 to-teal-400 bg-clip-text text-transparent">能量流動定位儀</span>
        </h1>
        <p class="text-gray-400 max-w-2xl mx-auto text-sm sm:text-base">
          不同於靜態的性格分類（如 MBTI），IACD 側重於<strong>當下生命能量的運作模式</strong>。透過四大維度的座標化，透視你目前是在「建設」還是「防禦」，指引你重塑生命意義的航道。
        </p>
      </div>

      <!-- Dimension Showcase Cards -->
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
        <div class="bg-gray-900/40 border border-gray-800/80 p-5 rounded-2xl relative overflow-hidden group hover:border-purple-500/50 transition">
          <div class="absolute top-0 right-0 w-24 h-24 bg-purple-500/5 rounded-full blur-xl group-hover:bg-purple-500/10 transition"></div>
          <div class="flex items-start space-x-3">
            <span class="text-2xl font-bold text-purple-400">I</span>
            <div>
              <h3 class="text-sm font-bold text-white mb-1">Integration / 整合度 (S vs F)</h3>
              <p class="text-xs text-gray-400">你與過去的經歷是否和解？當下狀態是否連貫？</p>
              <div class="mt-2 flex space-x-2 text-[10px]">
                <span class="bg-purple-950/40 text-purple-300 px-2 py-0.5 rounded">S - Solid 穩固</span>
                <span class="bg-purple-950/40 text-purple-300 px-2 py-0.5 rounded">F - Fragmented 破碎</span>
              </div>
            </div>
          </div>
        </div>

        <div class="bg-gray-900/40 border border-gray-800/80 p-5 rounded-2xl relative overflow-hidden group hover:border-indigo-500/50 transition">
          <div class="absolute top-0 right-0 w-24 h-24 bg-indigo-500/5 rounded-full blur-xl group-hover:bg-indigo-500/10 transition"></div>
          <div class="flex items-start space-x-3">
            <span class="text-2xl font-bold text-indigo-400">A</span>
            <div>
              <h3 class="text-sm font-bold text-white mb-1">Activity / 主動性 (P vs R)</h3>
              <p class="text-xs text-gray-400">你對待生活的態度是主動爭取還是被動防禦？</p>
              <div class="mt-2 flex space-x-2 text-[10px]">
                <span class="bg-indigo-950/40 text-indigo-300 px-2 py-0.5 rounded">P - Proactive 主動</span>
                <span class="bg-indigo-950/40 text-indigo-300 px-2 py-0.5 rounded">R - Resistant 防禦</span>
              </div>
            </div>
          </div>
        </div>

        <div class="bg-gray-900/40 border border-gray-800/80 p-5 rounded-2xl relative overflow-hidden group hover:border-teal-500/50 transition">
          <div class="absolute top-0 right-0 w-24 h-24 bg-teal-500/5 rounded-full blur-xl group-hover:bg-teal-500/10 transition"></div>
          <div class="flex items-start space-x-3">
            <span class="text-2xl font-bold text-teal-400">C</span>
            <div>
              <h3 class="text-sm font-bold text-white mb-1">Connection / 連結方式 (O vs E)</h3>
              <p class="text-xs text-gray-400">你的能量是向內收縮還是向外利他擴散？</p>
              <div class="mt-2 flex space-x-2 text-[10px]">
                <span class="bg-teal-950/40 text-teal-300 px-2 py-0.5 rounded">O - Outward 利他</span>
                <span class="bg-teal-950/40 text-teal-300 px-2 py-0.5 rounded">E - Egocentric 自我</span>
              </div>
            </div>
          </div>
        </div>

        <div class="bg-gray-900/40 border border-gray-800/80 p-5 rounded-2xl relative overflow-hidden group hover:border-pink-500/50 transition">
          <div class="absolute top-0 right-0 w-24 h-24 bg-pink-500/5 rounded-full blur-xl group-hover:bg-pink-500/10 transition"></div>
          <div class="flex items-start space-x-3">
            <span class="text-2xl font-bold text-pink-400">D</span>
            <div>
              <h3 class="text-sm font-bold text-white mb-1">Direction / 方向感 (C vs V)</h3>
              <p class="text-xs text-gray-400">你對未來的藍圖是清晰可控還是模糊隨緣？</p>
              <div class="mt-2 flex space-x-2 text-[10px]">
                <span class="bg-pink-950/40 text-pink-300 px-2 py-0.5 rounded">C - Clear 清晰</span>
                <span class="bg-pink-950/40 text-pink-300 px-2 py-0.5 rounded">V - Vague 模糊</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modes Selection Box -->
      <div class="bg-gradient-to-b from-gray-900 to-gray-950 border border-gray-800 p-6 rounded-2xl glow-purple text-center space-y-6">
        <div>
          <h2 class="text-lg font-bold text-white">啟動能量光譜分析</h2>
          <p class="text-xs text-gray-400 mt-1">我們為您準備了兩種診斷模式，您可以依當下心境選擇。</p>
        </div>

        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <button onclick="startTest('quick')" class="flex-1 bg-gradient-to-r from-purple-600 to-indigo-600 hover:from-purple-500 hover:to-indigo-500 text-white font-semibold py-4 px-6 rounded-xl shadow-lg shadow-purple-950/50 hover:shadow-purple-500/20 hover:scale-[1.01] transition-all-300 flex flex-col items-center">
            <span class="text-base">🚀 快速體驗診斷</span>
            <span class="text-[10px] text-purple-200 mt-0.5 font-normal">精選 32 題 • 約 3 分鐘 • 均衡涵蓋各維度</span>
          </button>

          <button onclick="startTest('full')" class="flex-1 bg-gray-900 hover:bg-gray-800/80 border border-gray-800 hover:border-gray-700 text-white font-semibold py-4 px-6 rounded-xl shadow-md hover:scale-[1.01] transition-all-300 flex flex-col items-center">
            <span class="text-base text-teal-400">🔬 完整深度診斷</span>
            <span class="text-[10px] text-gray-400 mt-0.5 font-normal">專業 144 題 • 約 12 分鐘 • 最強效度的精準報告</span>
          </button>
        </div>
      </div>
    </section>

    <!-- Screen 2: Diagnostic (Test) Section -->
    <section id="test-screen" class="hidden space-y-6">
      <!-- Info Header -->
      <div class="flex justify-between items-center bg-gray-900/60 border border-gray-800 p-4 rounded-xl">
        <div>
          <span id="test-mode-badge" class="bg-gray-800 text-gray-300 text-[10px] px-2 py-1 rounded-md font-medium uppercase">快速診斷模式</span>
          <h2 id="current-section-title" class="text-sm font-bold text-white mt-1">工作與現實情況</h2>
        </div>
        <div class="text-right">
          <span id="progress-text" class="text-xs text-gray-400 font-mono">1 / 6 頁</span>
        </div>
      </div>

      <!-- Global Progress Bar -->
      <div class="w-full bg-gray-800 h-2 rounded-full overflow-hidden">
        <div id="progress-bar-fill" class="bg-gradient-to-r from-purple-500 via-indigo-500 to-teal-500 h-full w-0 transition-all duration-300"></div>
      </div>

      <!-- Paginated Questions Form -->
      <div id="questions-container" class="space-y-4">
        <!-- Dynamically injected cards of questions -->
      </div>

      <!-- Action Navigation -->
      <div class="flex justify-between items-center pt-4">
        <button id="prev-btn" onclick="prevPage()" class="bg-gray-900 hover:bg-gray-800 border border-gray-800 hover:border-gray-700 text-gray-300 font-medium py-2.5 px-5 rounded-xl text-sm transition">
          上一頁
        </button>
        <span class="text-xs text-gray-500 hidden sm:inline">答完所有問題即可進入下一步</span>
        <button id="next-btn" onclick="nextPage()" class="bg-gradient-to-r from-purple-600 to-indigo-600 hover:from-purple-500 hover:to-indigo-500 text-white font-semibold py-2.5 px-6 rounded-xl text-sm shadow-md transition">
          下一頁
        </button>
      </div>
    </section>

    <!-- Screen 3: Analyzing Screen -->
    <section id="analyzing-screen" class="hidden py-16 text-center space-y-6">
      <div class="relative w-24 h-24 mx-auto">
        <!-- Outer Spinner -->
        <div class="absolute inset-0 rounded-full border-4 border-purple-500/20 border-t-purple-500 animate-spin"></div>
        <!-- Inner Glow -->
        <div class="absolute inset-2 rounded-full bg-gradient-to-br from-indigo-900/50 to-teal-900/50 blur-sm"></div>
      </div>
      <div class="space-y-2">
        <h3 class="text-lg font-bold text-white animate-pulse">正在解構生命能量光譜...</h3>
        <p class="text-xs text-gray-400 max-w-sm mx-auto">正在分析 4 個維度（整合、主動、連結、方向）的相互疊加，並將您的生命能量座標化...</p>
      </div>
    </section>

    <!-- Screen 4: Results Dashboard -->
    <section id="results-screen" class="hidden space-y-8">
      
      <!-- Archetype Profile Badge Section -->
      <div class="bg-gradient-to-r from-indigo-950 via-gray-900 to-slate-900 border border-indigo-800/60 p-6 rounded-3xl relative overflow-hidden">
        <div class="absolute -right-16 -top-16 w-48 h-48 bg-purple-500/10 rounded-full blur-3xl"></div>
        <div class="absolute -left-16 -bottom-16 w-48 h-48 bg-teal-500/10 rounded-full blur-3xl"></div>
        
        <div class="flex flex-col md:flex-row md:items-center justify-between gap-6 relative z-10">
          <div class="space-y-3">
            <span class="text-xs font-semibold bg-indigo-500/10 border border-indigo-800 text-indigo-300 px-3 py-1 rounded-full">
              診斷結果定位：<span id="res-formula-top">SPOC</span> 型
            </span>
            <h1 class="text-3xl sm:text-4xl font-extrabold text-white flex items-center">
              <span id="res-archetype-name" class="bg-gradient-to-r from-white via-gray-100 to-gray-300 bg-clip-text">使命舵手</span>
            </h1>
            <p id="res-short-description" class="text-gray-300 text-sm max-w-xl">
              在心理與社會層面上，代表了一種「整合性極高」的生命狀態。這類人不僅僅是「強者」，更是一位「活得通透」的人。
            </p>
          </div>
          <!-- Big Glowing Code Plate -->
          <div class="bg-slate-950/80 border border-gray-800 px-6 py-4 rounded-2xl flex flex-col items-center justify-center glow-purple min-w-[140px] text-center self-start md:self-center">
            <span id="res-formula-card" class="text-4xl font-black bg-gradient-to-r from-purple-400 via-indigo-300 to-teal-400 bg-clip-text text-transparent tracking-widest">SPOC</span>
            <span class="text-[10px] text-gray-400 mt-1 font-medium tracking-wider uppercase">生命引力場組合</span>
          </div>
        </div>
      </div>

      <!-- Quick Toggle Tab Area -->
      <div class="flex border-b border-gray-800">
        <button onclick="switchTab('tab-report')" id="tab-btn-report" class="flex-1 py-3 text-center text-sm font-semibold border-b-2 border-purple-500 text-purple-400 transition-all">能量報告書</button>
        <button onclick="switchTab('tab-calibrator')" id="tab-btn-calibrator" class="flex-1 py-3 text-center text-sm font-semibold text-gray-400 hover:text-white transition-all">維度調校儀 (微調互動)</button>
        <button onclick="switchTab('tab-gaps')" id="tab-btn-gaps" class="flex-1 py-3 text-center text-sm font-semibold text-gray-400 hover:text-white transition-all flex items-center justify-center space-x-1">
          <span>解鎖人生指引</span>
        </button>
      </div>

      <!-- Tab Content 1: Full Report -->
      <div id="tab-report" class="tab-panel space-y-6">
        
        <!-- Dimensional Scores Chart Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <!-- Score breakdown card -->
          <div class="bg-gray-900/30 border border-gray-800/80 p-5 rounded-2xl space-y-4">
            <h3 class="text-sm font-bold text-white">4D 生命能量光譜量值</h3>
            <div id="dimensional-gauges" class="space-y-4">
              <!-- Dynamically rendered custom gauge progress bars -->
            </div>
          </div>

          <!-- Radar SVG Section -->
          <div class="bg-gray-900/30 border border-gray-800/80 p-5 rounded-2xl flex flex-col items-center justify-center">
            <h3 class="text-sm font-bold text-white mb-2 self-start">能量象限地圖</h3>
            <div id="radar-container" class="w-48 h-48 flex items-center justify-center relative">
              <!-- Custom Interactive SVG Radar -->
            </div>
            <div class="flex justify-between w-full mt-2 text-[10px] text-gray-400 px-2">
              <span class="text-purple-400">I-整合度</span>
              <span class="text-indigo-400">A-主動性</span>
              <span class="text-teal-400">C-連結方式</span>
              <span class="text-pink-400">D-方向感</span>
            </div>
          </div>
        </div>

        <!-- In-depth analysis modules -->
        <div class="space-y-4">
          <!-- Section 1 -->
          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl">
            <h3 class="text-base font-bold text-white flex items-center space-x-2">
              <span class="w-1.5 h-4 bg-purple-500 rounded-full inline-block"></span>
              <span>1. 這是怎樣的生命狀態？</span>
            </h3>
            <p id="res-state-p" class="text-sm text-gray-300 mt-3 leading-relaxed whitespace-pre-wrap">...</p>
          </div>

          <!-- Section 2 -->
          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl">
            <h3 class="text-base font-bold text-white flex items-center space-x-2">
              <span class="w-1.5 h-4 bg-indigo-500 rounded-full inline-block"></span>
              <span>2. 值得欣賞的特質</span>
            </h3>
            <p id="res-strengths-p" class="text-sm text-gray-300 mt-3 leading-relaxed whitespace-pre-wrap">...</p>
          </div>

          <!-- Section 3 -->
          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl">
            <h3 class="text-base font-bold text-white flex items-center space-x-2">
              <span class="w-1.5 h-4 bg-teal-500 rounded-full inline-block"></span>
              <span>3. 改善與提升建議</span>
            </h3>
            <p id="res-advices-p" class="text-sm text-gray-300 mt-3 leading-relaxed whitespace-pre-wrap">...</p>
          </div>

          <!-- Section 4 (Conditional based on results file) -->
          <div id="res-peer-box" class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl">
            <h3 class="text-base font-bold text-white flex items-center space-x-2">
              <span class="w-1.5 h-4 bg-pink-500 rounded-full inline-block"></span>
              <span>4. 同行夥伴與提醒關係</span>
            </h3>
            <p id="res-peers-p" class="text-sm text-gray-300 mt-3 leading-relaxed whitespace-pre-wrap">...</p>
          </div>

          <!-- Quote Block -->
          <div class="bg-gradient-to-br from-purple-950/20 to-gray-900 border border-purple-900/30 p-5 rounded-2xl italic text-center text-sm text-purple-200">
            💡 <span id="res-quote-span">"保持你的清晰，但偶爾允許自己隨浪而行。"</span>
          </div>
        </div>

      </div>

      <!-- Tab Content 2: Energy Calibration Tool -->
      <div id="tab-calibrator" class="tab-panel hidden space-y-6">
        <div class="bg-gray-900/30 border border-purple-800/30 p-5 rounded-2xl">
          <h3 class="text-base font-bold text-white">🎛️ 能量維度手動校調面板</h3>
          <p class="text-xs text-gray-400 mt-1">
            這套系統的核心假設之一是<strong>「能量的流動性」</strong>。當你意識到某個維度，並通過日常微調將其轉換，你的整體生命引力場就會跟著轉化。請在下方點擊撥動開關，感受不同引力場狀態。
          </p>
        </div>

        <div class="bg-slate-900 border border-gray-800 rounded-2xl p-6 space-y-6">
          <!-- 4 Toggles with rich descriptions -->
          <div class="flex items-center justify-between border-b border-gray-800/50 pb-4">
            <div>
              <span class="text-xs text-gray-500">I 維度（整合度）</span>
              <h4 class="text-sm font-bold text-white" id="toggle-i-label">穩固 Solid</h4>
              <p class="text-[11px] text-gray-400">與過去的經歷達成和解，內心穩定連續</p>
            </div>
            <button onclick="toggleCalibrate('I')" id="btn-toggle-I" class="relative inline-flex h-6 w-11 items-center rounded-full bg-purple-600 transition-colors">
              <span class="inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-6"></span>
            </button>
          </div>

          <div class="flex items-center justify-between border-b border-gray-800/50 pb-4">
            <div>
              <span class="text-xs text-gray-500">A 維度（主動性）</span>
              <h4 class="text-sm font-bold text-white" id="toggle-a-label">主動 Proactive</h4>
              <p class="text-[11px] text-gray-400">採取主導行動、策略應對，拒絕隨波逐流</p>
            </div>
            <button onclick="toggleCalibrate('A')" id="btn-toggle-A" class="relative inline-flex h-6 w-11 items-center rounded-full bg-indigo-600 transition-colors">
              <span class="inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-6"></span>
            </button>
          </div>

          <div class="flex items-center justify-between border-b border-gray-800/50 pb-4">
            <div>
              <span class="text-xs text-gray-500">C 維度（連結方式）</span>
              <h4 class="text-sm font-bold text-white" id="toggle-c-label">利他 Outward</h4>
              <p class="text-[11px] text-gray-400">將心力與社會責任鏈接，謀求共赢與共好</p>
            </div>
            <button onclick="toggleCalibrate('C')" id="btn-toggle-C" class="relative inline-flex h-6 w-11 items-center rounded-full bg-teal-600 transition-colors">
              <span class="inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-6"></span>
            </button>
          </div>

          <div class="flex items-center justify-between pb-2">
            <div>
              <span class="text-xs text-gray-500">D 維度（方向感）</span>
              <h4 class="text-sm font-bold text-white" id="toggle-d-label">清晰 Clear</h4>
              <p class="text-[11px] text-gray-400">清晰的生命目標，高抗干擾的行動導航</p>
            </div>
            <button onclick="toggleCalibrate('D')" id="btn-toggle-D" class="relative inline-flex h-6 w-11 items-center rounded-full bg-pink-600 transition-colors">
              <span class="inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-6"></span>
            </button>
          </div>
        </div>

        <div class="bg-gray-900/30 border border-gray-800 p-5 rounded-2xl text-center">
          <p class="text-xs text-gray-400">
            💡 此處為「互動調校」模式，不會覆蓋您實際測驗的核心分數，供您探索其他 15 種生命形態。
          </p>
        </div>
      </div>

      <!-- Tab Content 3: Life Direction Plan -->
      <div id="tab-gaps" class="tab-panel hidden space-y-6">
        <div class="bg-gradient-to-r from-teal-950/20 to-indigo-950/20 border border-teal-850 p-6 rounded-2xl space-y-4">
          <h2 class="text-lg font-bold text-white">🔍 識別「意義的斷層」與重塑計畫</h2>
          <p class="text-sm text-gray-300">
            你被診斷為 <strong id="plan-code" class="text-teal-400">SPOC</strong> 型，這代表你當下的生命力正聚焦於這個特定的能量軌道。
          </p>
        </div>

        <div class="space-y-6">
          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl space-y-3">
            <h3 class="text-sm font-bold text-white text-teal-400 uppercase">第一步：定位與診斷 (Self-Audit)</h3>
            <p id="audit-text-p" class="text-sm text-gray-300 leading-relaxed">
              當前診斷提示了你的防禦與建設占比。如果你正經歷痛苦、疲憊、或漫無目的地空轉，痛苦並非單純源於環境，而是你的能量模式在進行「代償性損耗」。
            </p>
          </div>

          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl space-y-3">
            <h3 class="text-sm font-bold text-white text-indigo-400 uppercase">第二步：修補「意義的斷層」</h3>
            <div id="gap-instruction-box" class="text-sm text-gray-300 space-y-2">
              <!-- Dynamically rendered based on whether direction is Vague or Clear -->
            </div>
          </div>

          <div class="bg-gray-900/30 border border-gray-800 p-6 rounded-2xl space-y-3">
            <h3 class="text-sm font-bold text-white text-purple-400 uppercase">第三步：維度微調 (Micro-Calibration)</h3>
            <div id="calibration-instruction-box" class="text-sm text-gray-300 space-y-2">
              <!-- Dynamic Micro action items based on profile -->
            </div>
          </div>
        </div>
      </div>

    </section>

  </main>

  <footer class="text-center py-8 text-xs text-gray-600 border-t border-gray-900 max-w-4xl mx-auto">
    <p>© 2026 IACD Life Energy Diagnostic System. All rights reserved.</p>
    <p class="mt-1">透過能量光譜檢驗、微調機制與行動指引，解鎖你的真實生命航線。</p>
  </footer>

  <!-- Internal Script: Contains entire IACD Questions, scoring formulas, types profile lookup -->
  <script>
    // 144 Questions raw data
    const questionsList = [
      // WORK & REALITY (1-36)
      { id: 1, section: "工作與現實情況", text: "當我在工作上遇到挫折時，我能一眼看出這與我過去處理困境的模式有何關聯。", dim: "S" },
      { id: 2, section: "工作與現實情況", text: "我覺得自己目前的經濟困境，與我早年學習金錢管理的經驗幾乎沒有關係。", dim: "F", isReverse: true },
      { id: 3, section: "工作與現實情況", text: "回顧過去的求職或生活經歷，我能列舉出哪些特質幫我撐到了今天，並運用在現在的工作中。", dim: "S" },
      { id: 4, section: "工作與現實情況", text: "我覺得無論我過去有多努力，現在的職場環境總是令我感到陌生且無所適從。", dim: "F" },
      { id: 5, section: "工作與現實情況", text: "在處理經濟問題時，我習慣檢視過去的決策失誤，並將其視為未來改善的寶貴資訊。", dim: "S" },
      { id: 6, section: "工作與現實情況", text: "我常覺得自己的職業生涯支離破碎，過去的努力與現在的狀態好像處於兩個平行時空。", dim: "F" },
      { id: 7, section: "工作與現實情況", text: "面對金錢壓力，我能明白為什麼自己會產生焦慮，因為我知道這種不安感起源於我過去的哪一段經歷。", dim: "S" },
      { id: 8, section: "工作與現實情況", text: "我對於職場上的不公平感感到無比憤怒，但說不出這種憤怒除了環境原因之外，是否與我自身的成長背景有關。", dim: "F" },
      { id: 9, section: "工作與現實情況", text: "我認為過往的失敗經驗，是我現在職場韌性的重要基石，我接納那些經歷。", dim: "S" },
      { id: 10, section: "工作與現實情況", text: "當我不順利時，我傾向認為是運氣不好，過去發生的事情對我的決策能力並沒有具體的啟發。", dim: "F" },
      { id: 11, section: "工作與現實情況", text: "當我發現現職工作無法滿足我的財務需求時，我會主動規劃轉職、兼職或進修，而不是等待加薪。", dim: "P" },
      { id: 12, section: "工作與現實情況", text: "我覺得目前的經濟狀況很大程度上取決於大環境或老闆的決定，我個人能做的其實很少。", dim: "R" },
      { id: 13, section: "工作與現實情況", text: "即便在工作負荷很重的情況下，我仍會嘗試建立一套適合自己的工作節奏，以維持基本生活品質。", dim: "P" },
      { id: 14, section: "工作與現實情況", text: "每當我嘗試改變經濟現狀，總是遇到各種阻力，久而久之我習慣了接受現狀。", dim: "R" },
      { id: 15, section: "工作與現實情況", text: "面對未知的職場挑戰，我傾向於主動蒐集資訊並試圖制定應對方案。", dim: "P" },
      { id: 16, section: "工作與現實情況", text: "我常感覺在職場中處於「被選擇」的位置，我對自己的職業發展缺乏真正的控制感。", dim: "R" },
      { id: 17, section: "工作與現實情況", text: "當我的財務狀況出現困難時，我會主動列出預算並尋求資源，積極尋找改變的契機。", dim: "P" },
      { id: 18, section: "工作與現實情況", text: "我對於改善自己的經濟條件感到心灰意冷，因為無論我如何努力，結果往往無法如預期。", dim: "R" },
      { id: 19, section: "工作與現實情況", text: "我選擇工作時，除了薪酬之外，更看重這份工作能否對他人或社會帶來實際的貢獻。", dim: "O" },
      { id: 20, section: "工作與現實情況", text: "對我而言，賺錢的主要目的是為了確保自己的個人生活無憂，其他人的需求不在我的考量範圍內。", dim: "E" },
      { id: 21, section: "工作與現實情況", text: "我在職場中感到最滿足的時刻，往往是我協助同事解決問題或是團隊達成共同目標時。", dim: "O" },
      { id: 22, section: "工作與現實情況", text: "我認為職場是一個競爭激烈的環境，與其關心他人，不如先確保自己在經濟上的絕對優勢。", dim: "E" },
      { id: 23, section: "工作與現實情況", text: "當我進行財務規劃時，我會將「如何幫助家人或回饋社區」列為重要的考慮因素。", dim: "O" },
      { id: 24, section: "工作與現實情況", text: "我覺得如果工作不能直接提升我的社會地位或物質生活，那它就失去了存在的價值。", dim: "E" },
      { id: 25, section: "工作與現實情況", text: "我願意在工作之餘投入資源去支援弱勢或推動公義，即便這會犧牲我個人的休閒或財務收益。", dim: "O" },
      { id: 26, section: "工作與現實情況", text: "我傾向於將工作視為個人的「私事」，我不喜歡我的職業選擇與社會大眾或他人福祉扯上關係。", dim: "E" },
      { id: 27, section: "工作與現實情況", text: "我經常思考我的職業技能如何能成為社會的橋樑，連結不同需求的群體。", dim: "O" },
      { id: 28, section: "工作與現實情況", text: "即使在忙碌的日常工作中，我也非常清楚自己未來三至五年的職涯發展藍圖。", dim: "C" },
      { id: 29, section: "工作與現實情況", text: "我對於自己的經濟未來感到茫然，通常只希望能活過這一個月就好。", dim: "V" },
      { id: 30, section: "工作與現實情況", text: "我能清楚說出我目前的工作經歷，如何一步步為我未來的理想目標打下基礎。", dim: "C" },
      { id: 31, section: "工作與現實情況", text: "在職場上，我常常覺得自己像是在「漂流」，並沒有一個具體的目的地在指引我。", dim: "V" },
      { id: 32, section: "工作與現實情況", text: "每當有新的工作機會或財務選擇時，我都能根據自己的長期目標迅速做出判斷。", dim: "C" },
      { id: 33, section: "工作與現實情況", text: "我對未來的規劃僅停留在「如果有好機會再說」的層次，沒有主動設定過目標。", dim: "V" },
      { id: 34, section: "工作與現實情況", text: "我有一套明確的財務目標，並且每天都在根據這些目標檢視自己的消費與儲蓄行為。", dim: "C" },
      { id: 35, section: "工作與現實情況", text: "當別人問我五年後想成為什麼樣的人，或想達到什麼經濟狀態時，我感到很難回答。", dim: "V" },
      { id: 36, section: "工作與現實情況", text: "我不僅有大方向的目標，還能將其拆解為每一季、每一週可執行的具體行動計劃。", dim: "C" },

      // INTERPERSONAL RELATIONSHIPS (37-72)
      { id: 37, section: "人際關係情境", text: "當我在一段關係中感到受傷或被忽略時，我會主動向對方表達我的感受，而不是獨自生悶氣。", dim: "P" },
      { id: 38, section: "人際關係情境", text: "我覺得在人際互動中，我總是處於被動等待對方的態度，我不相信我能主動影響關係的走向。", dim: "R" },
      { id: 39, section: "人際關係情境", text: "即使我對過往的人際創傷仍感到不安，我也會刻意在現在的互動中練習建立健康界限。", dim: "P" },
      { id: 40, section: "人際關係情境", text: "當人際關係出現衝突時，我傾向於選擇「斷聯」或「逃避」，因為我覺得處理這些衝突實在太過沉重。", dim: "R" },
      { id: 41, section: "人際關係情境", text: "我會定期反思自己的人際需求，並主動尋找能支持我的人際網絡，而不是等待別人來關心我。", dim: "P" },
      { id: 42, section: "人際關係情境", text: "我常感覺自己像是一個在關係中隨波逐流的客體，別人的肯定或否定直接決定了我的心情。", dim: "R" },
      { id: 43, section: "人際關係情境", text: "如果我發現一段關係對我造成持續的心理耗竭，我有能力主動做出調整或減少互動。", dim: "P" },
      { id: 44, section: "人際關係情境", text: "我很怕在關係中表達真實需求，因為我害怕一旦我表現出「需要」，就會被嫌棄或被拋棄。", dim: "R" },
      { id: 45, section: "人際關係情境", text: "在與人互動時，我會真心關注對方的生命故事與成長，而不僅僅是交換資訊。", dim: "O" },
      { id: 46, section: "人際關係情境", text: "除非對方對我有實質利益，否則我很少主動花時間去維持一個人際關係。", dim: "E" },
      { id: 47, section: "人際關係情境", text: "我認為經營一段健康的人際關係，核心在於互相尊重並共同創造社會價值。", dim: "O" },
      { id: 48, section: "人際關係情境", text: "我在人際關係中最在意的，是對方能否隨時滿足我的情感需求或支持我的個人計劃。", dim: "E" },
      { id: 49, section: "人際關係情境", text: "當身邊的朋友遇到困難時，即使會耗費我的時間，我也會主動提供協助，因為我覺得這是互助的責任。", dim: "O" },
      { id: 50, section: "人際關係情境", text: "我經營社交圈的主要目的，是為了讓自己看起來更有地位，或者確保我能擁有更多資源。", dim: "E" },
      { id: 51, section: "人際關係情境", text: "我喜歡與不同背景的人交流，並嘗試理解他們的世界，即使這與我個人的利益無關。", dim: "O" },
      { id: 52, section: "人際關係情境", text: "對我而言，人際關係中的「給予」是一種壓力，我更偏好維持「各取所需」的互動關係。", dim: "E" },
      { id: 53, section: "人際關係情境", text: "我相信透過深度的情感連結，我們可以共同對周遭的人群產生正面影響力。", dim: "O" },
      { id: 54, section: "人際關係情境", text: "當一段關係無法再帶給我樂趣或滿足時，我會迅速斷開連結，我不認為我有責任去經營一段無利可圖的關係。", dim: "E" },
      { id: 55, section: "人際關係情境", text: "我有非常清晰的標準，知道什麼樣的朋友或伴侶值得我投入深厚的情感。", dim: "C" },
      { id: 56, section: "人際關係情境", text: "我經常發現自己陷入一些讓我感到不舒服的人際關係中，卻不知道該如何抽身或改善。", dim: "V" },
      { id: 57, section: "人際關係情境", text: "當我與人交往時，我會審視這段關係是否能支持我的人生方向或價值觀。", dim: "C" },
      { id: 58, section: "人際關係情境", text: "我覺得自己的人際關係很隨緣，身邊有誰就是誰，從未主動去規劃過我想要怎樣的社交圈。", dim: "V" },
      { id: 59, section: "人際關係情境", text: "面對人際關係的選擇，我能冷靜判斷這段關係是應該深交、疏遠，還是止步於點頭之交。", dim: "C" },
      { id: 60, section: "人際關係情境", text: "我常因為害怕孤獨或不想拒絕別人，而勉強維持一些對我來說毫無意義的人際互動。", dim: "V" },
      { id: 61, section: "人際關係情境", text: "我為自己的人際互動設定了明確的目標，例如：與能激勵我成長的人多連結，遠離耗能的人。", dim: "C" },
      { id: 62, section: "人際關係情境", text: "我不清楚自己在關係中追求的是什麼（例如：陪伴、合作、自我證明），總是走一步算一步。", dim: "V" },
      { id: 63, section: "人際關係情境", text: "當我的人生階段轉變時，我有意識地調整我的人際網絡，以匹配我現階段的生活重心。", dim: "C" },
      { id: 64, section: "人際關係情境", text: "我能夠清楚理解自己過往的成長背景，如何影響我現在選擇伴侶或朋友的偏好。", dim: "S" },
      { id: 65, section: "人際關係情境", text: "只要提到過去的某段關係，我馬上會感到情緒混亂，甚至無法連貫地說出那段經歷的細節。", dim: "F" },
      { id: 66, section: "人際關係情境", text: "我能將過去人際關係中的挫敗轉化為智慧，並運用在現在的相處中，而不重蹈覆轍。", dim: "S" },
      { id: 67, section: "人際關係情境", text: "我覺得自己的人際模式非常破碎，我在不同朋友面前彷彿是完全不同的人，讓我感到很疲憊。", dim: "F" },
      { id: 68, section: "人際關係情境", text: "當我遭遇人際衝突時，我不會感到自己整個人被摧毀，因為我對自己的價值有穩固的自我認知。", dim: "S" },
      { id: 69, section: "人際關係情境", text: "我常感覺自己像是一個「情感漂浮者」，過去的關係像霧一樣散去，留不下任何能滋養現在的力量。", dim: "F" },
      { id: 70, section: "人際關係情境", text: "我能意識到自己在人際關係中重覆的舊習慣（如：過度索求或過度迴避），並願意面對其根源。", dim: "S" },
      { id: 71, section: "人際關係情境", text: "我無法將現在的關係與過往的經歷連結起來，這讓我感覺我的人際生活總是處於不斷「重啟」的狀態。", dim: "F" },
      { id: 72, section: "人際關係情境", text: "我接納過去所有的人際創傷與美好，這些經歷共同編織成了現在我與人相處的底蘊。", dim: "S" },

      // INNER WORLD & EMOTIONS (73-108)
      { id: 73, section: "內心世界及情緒", text: "我能平靜地接受自己過去曾犯過的錯誤，不覺得那是現在的污點。", dim: "S" },
      { id: 74, section: "內心世界及情緒", text: "當情緒劇烈波動時，我常覺得自己好像變成了另一個人，無法與平時的自己連結。", dim: "F" },
      { id: 75, section: "內心世界及情緒", text: "我能清楚分辨當下的情緒是因為現在的事，還是被過去的回憶觸發。", dim: "S" },
      { id: 76, section: "內心世界及情緒", text: "對我而言，過去的痛苦經歷像是一種揮之不去的陰影，常在我不經意時干擾現在的生活。", dim: "F" },
      { id: 77, section: "內心世界及情緒", text: "我對自己的性格有連貫的認知，不會因為遭遇小挫折就覺得自己徹底失敗。", dim: "S" },
      { id: 78, section: "內心世界及情緒", text: "我常有「我是誰？我為什麼變成這樣？」的茫然感，覺得內在有很多斷裂的部分。", dim: "F" },
      { id: 79, section: "內心世界及情緒", text: "我能將內心的創傷與成長經歷，視為構成我生命的一部分，而不僅是負擔。", dim: "S" },
      { id: 80, section: "內心世界及情緒", text: "我很難回顧過去，因為記憶對我來說往往伴隨著混亂或令人痛苦的情緒斷層。", dim: "F" },
      { id: 81, section: "內心世界及情緒", text: "我感受到內心的穩定感，過去的經歷與現在的自我像是一個統一的整體。", dim: "S" },
      { id: 82, section: "內心世界及情緒", text: "當負面情緒來襲時，我會主動嘗試轉移注意力或練習呼吸，而不是沉溺其中。", dim: "P" },
      { id: 83, section: "內心世界及情緒", text: "我常覺得情緒像一場大浪，我除了被動承受痛苦外，別無他法。", dim: "R" },
      { id: 84, section: "內心世界及情緒", text: "我有信心可以透過練習自我對話，改變自己看待挫折的角度。", dim: "P" },
      { id: 85, section: "內心世界及情緒", text: "面對極度低落的狀態，我往往只能等待它自己慢慢消失，感覺自己完全無力扭轉。", dim: "R" },
      { id: 86, section: "內心世界及情緒", text: "我會主動去覺察那些讓我不安的情緒，並試著理清其背後的訊息。", dim: "P" },
      { id: 87, section: "內心世界及情緒", text: "情緒波動時，我感覺自己像是一個受害者，容易被環境中的微小變化所左右。", dim: "R" },
      { id: 88, section: "內心世界及情緒", text: "當內心感到失衡時，我會主動尋找能讓我感到平靜的活動來自我修復。", dim: "P" },
      { id: 89, section: "內心世界及情緒", text: "我覺得自己對情緒的影響力很低，常常被突如其來的低潮打亂生活步調。", dim: "R" },
      { id: 90, section: "內心世界及情緒", text: "我有意識地管理自己的心理能量，不會讓自己長時間處於消耗狀態。", dim: "P" },
      { id: 91, section: "內心世界及情緒", text: "我在獨處時，常會思考如何讓自己成為一個更好的人，以便未來能更好地服務他人。", dim: "O" },
      { id: 92, section: "內心世界及情緒", text: "我在處理情緒時，最關心的是「這對我個人有什麼損失」，而非我與他人的關係。", dim: "E" },
      { id: 93, section: "內心世界及情緒", text: "我相信我的情緒體驗也是人類共同體驗的一部分，這讓我比較能同理他人。", dim: "O" },
      { id: 94, section: "內心世界及情緒", text: "當我陷入低谷時，我只關注自己的苦難，很難去顧及周遭人的感受。", dim: "E" },
      { id: 95, section: "內心世界及情緒", text: "我追求內心的平靜，是因為我希望這種平靜能成為周遭人的一種穩定力量。", dim: "O" },
      { id: 96, section: "內心世界及情緒", text: "我努力整理情緒的主要動力，是為了確保自己的私人生活能舒適、不受他人干擾。", dim: "E" },
      { id: 97, section: "內心世界及情緒", text: "即使在情緒困難時期，我依然會嘗試思考我的痛苦如何轉化為對社會或群體的理解。", dim: "O" },
      { id: 98, section: "內心世界及情緒", text: "我覺得內心的世界是絕對私有的，我不希望我的情緒與任何外在的義務或他人扯上關係。", dim: "E" },
      { id: 99, section: "內心世界及情緒", text: "我將內在的修煉視為一種責任，這能讓我成為社會的一份溫暖力量。", dim: "O" },
      { id: 100, section: "內心世界及情緒", text: "我對於自己理想中「心理成熟」的狀態有明確的標準。", dim: "C" },
      { id: 101, section: "內心世界及情緒", text: "我常覺得內心漫無目的地消耗時間，不知道自己追求心理平靜到底為了什麼。", dim: "V" },
      { id: 102, section: "內心世界及情緒", text: "我每天都會有意識地檢視自己的心情，並朝著更健康的心理狀態邁進。", dim: "C" },
      { id: 103, section: "內心世界及情緒", text: "對於未來的內心願景，我感到模糊，不清楚什麼樣的心理狀態才是我真正想要的。", dim: "V" },
      { id: 104, section: "內心世界及情緒", text: "我有一套幫助自己對抗情緒焦慮的系統（如日記、冥想、運動）。", dim: "C" },
      { id: 105, section: "內心世界及情緒", text: "當有人問我「你想成為什麼樣的人」時，我會對內在自我的目標感到困惑。", dim: "V" },
      { id: 106, section: "內心世界及情緒", text: "我清楚知道什麼樣的心理挑戰是我現在必須克服，並已在執行相關的改善計畫。", dim: "C" },
      { id: 107, section: "內心世界及情緒", text: "我對於克服內心恐懼沒有具體的目標，總是隨緣度日。", dim: "V" },
      { id: 108, section: "內心世界及情緒", text: "我將「心理自由」視為我的核心人生目標，並在生活中一步步落實。", dim: "C" },

      // CRISIS SITUATIONS (109-144)
      { id: 109, section: "突發危機情境", text: "面對危機，我能很快從過去克服類似困難的經驗中提取力量。", dim: "S" },
      { id: 110, section: "突發危機情境", text: "危機發生時，我感覺自己像碎了一地，完全無法維持原本的樣子。", dim: "F" },
      { id: 111, section: "突發危機情境", text: "我能理解這場危機是生命歷程的一部分，這對我來說並不意外。", dim: "S" },
      { id: 112, section: "突發危機情境", text: "我覺得這場危機是完全不講理的災難，它徹底切斷了我對未來的連結。", dim: "F" },
      { id: 113, section: "突發危機情境", text: "即使在慌亂中，我依然保有我作為人的核心價值與自我認同。", dim: "S" },
      { id: 114, section: "突發危機情境", text: "危機讓我產生強烈的解離感，彷彿正在發生的事與我無關。", dim: "F" },
      { id: 115, section: "突發危機情境", text: "我能迅速整理思緒，將這場危機與我的人生藍圖重新對接。", dim: "S" },
      { id: 116, section: "突發危機情境", text: "我感覺自己的人生在這一刻完全斷層，找不到與過去任何經驗的支撐點。", dim: "F" },
      { id: 117, section: "突發危機情境", text: "危機中，我依然能感受到自己的連續性，不會感到徹底迷失。", dim: "S" },
      { id: 118, section: "突發危機情境", text: "第一時間，我會主動列出待辦事項，試圖從微小的細節中掌控局面。", dim: "P" },
      { id: 119, section: "突發危機情境", text: "危機一來，我習慣先僵住，等待外界給予指示或援手。", dim: "R" },
      { id: 120, section: "突發危機情境", text: "即使資源受限，我依然會嘗試採取行動，而不只是乾坐著等待災難過去。", dim: "P" },
      { id: 121, section: "突發危機情境", text: "我覺得面對重大危機，個人的努力通常是無用的，只能聽天由命。", dim: "R" },
      { id: 122, section: "突發危機情境", text: "我會主動去尋找危機中的「生存窗口」，並進行嘗試。", dim: "P" },
      { id: 123, section: "突發危機情境", text: "我常因恐懼而選擇逃避，直到危機迫使我不得不面對時才處理。", dim: "R" },
      { id: 124, section: "突發危機情境", text: "即使情況惡劣，我也會嘗試發揮主動權，至少在情緒上保持穩定。", dim: "P" },
      { id: 125, section: "突發危機情境", text: "面對變數，我很容易感到無助，習慣性地陷入被動挨打的狀態。", dim: "R" },
      { id: 126, section: "突發危機情境", text: "我能迅速將危機拆解成可執行的步驟，並主動推進。", dim: "P" },
      { id: 127, section: "突發危機情境", text: "即使在危機中，我也會考慮我的決定對身邊重要的人會產生什麼影響。", dim: "O" },
      { id: 128, section: "突發危機情境", text: "危機當頭，我只關心如何保住我個人的利益，其他人顧不了那麼多。", dim: "E" },
      { id: 129, section: "突發危機情境", text: "我相信危機是連結人際網絡的時刻，我願意在保護自己的前提下尋求共贏。", dim: "O" },
      { id: 130, section: "突發危機情境", text: "我傾向於封閉起來，認為在危機中依靠任何人都是一種風險。", dim: "E" },
      { id: 131, section: "突發危機情境", text: "我願意在危機中運用資源去支持比我更脆弱的人，即使這對我自己不利。", dim: "O" },
      { id: 132, section: "突發危機情境", text: "我認為危機是個人戰，我只會優先滿足自己的基本安全需求。", dim: "E" },
      { id: 133, section: "突發危機情境", text: "即使在災難中，我依然能看見自己對群體或社會的一份責任。", dim: "O" },
      { id: 134, section: "突發危機情境", text: "我覺得危機讓我看透了人性的自私，我也會選擇只為自己盤算。", dim: "E" },
      { id: 135, section: "突發危機情境", text: "我會嘗試與他人連結並合作，相信集體的力量大於個人的掙扎。", dim: "O" },
      { id: 136, section: "突發危機情境", text: "危機爆發時，我有明確的「優先順序」，知道什麼是這階段必須先保住的。", dim: "C" },
      { id: 137, section: "突發危機情境", text: "我感到一片混亂，完全不知道該先處理什麼，目標極度模糊。", dim: "V" },
      { id: 138, section: "突發危機情境", text: "我能明確說出我希望透過這場危機，最終達到什麼樣的轉機。", dim: "C" },
      { id: 139, section: "突發危機情境", text: "我沒有長期導航，現在只想求生存，對危機後的未來毫無想法。", dim: "V" },
      { id: 140, section: "突發危機情境", text: "我有一套在危機中保持冷靜的指標，幫助我判斷何時該進、何時該退。", dim: "C" },
      { id: 141, section: "突發危機情境", text: "我覺得自己像在暴風雨中航行，完全看不見遠方的燈塔。", dim: "V" },
      { id: 142, section: "突發危機情境", text: "即便情況突變，我仍能修正目標，保持清晰的行動方向。", dim: "C" },
      { id: 143, section: "突發危機情境", text: "我沒有任何危機目標，通常是哪裡有動靜就往哪裡跑。", dim: "V" },
      { id: 144, section: "突發危機情境", text: "我明確知道即使失去一切，我最終想守住的底線是什麼。", dim: "C" }
    ];

    // Select subset for "Quick" assessment (32 items total, 8 per dimension)
    // S vs F (8 items): 1, 4, 64, 67, 73, 76, 109, 110
    // P vs R (8 items): 11, 12, 37, 38, 82, 83, 118, 119
    // O vs E (8 items): 19, 20, 45, 46, 91, 92, 127, 128
    // C vs V (8 items): 28, 29, 55, 56, 100, 101, 136, 137
    const quickQuestionIDs = [
      1, 4, 64, 67, 73, 76, 109, 110,
      11, 12, 37, 38, 82, 83, 118, 119,
      19, 20, 45, 46, 91, 92, 127, 128,
      28, 29, 55, 56, 100, 101, 136, 137
    ];

    // Dynamic 16 IACD Profiles Content
    const profilesDb = {
      "SPOC": {
        name: "使命舵手",
        desc: "「使命舵手」代表一種「整合性極高」的生命狀態。你活得通透、有力。你已經將過去的傷痕轉化為前進的燃料（S），主動掌控當下的境遇（P），將自我價值擴展到他人與社群（O），並且擁有一套極度清晰的內在導航系統（C）。",
        state: "這是一種「動態平衡」的狀態。\n• 內在的完整性 (S)：不避諱過去的經歷，失敗或創傷並非隱疾，而是刻在船體上的航行紀錄，展現真實且有份量的穩定感。\n• 外在的主導性 (P)：不等待機會，視外部環境為海況，調整自我的帆面主導人生方向。\n• 連結的擴展性 (O)：理解個人的存活必須與群體共好、回饋社區，這使得決策極具遠見與大局觀。\n• 目標的清晰度 (C)：自備強大的「願景過濾器」，面對誘惑和紛擾，能迅速聚焦核心使命。",
        strengths: "• 極高情緒轉化力 (S-F 軸優勢)：在挫敗中極快完成「感受-覺察-提取資源」的修復過程。\n• 困境「重幀」能力 (P-R 軸優勢)：第一反應是「這場危機如何作為下一步的踏腳石？」，韌性強大。\n• 穩定人心的磁場 (O-E 軸優勢)：能考慮他人利益，常在團隊扮演眾人定心丸的「錨點」。\n• 知行合一執行力 (C-V 軸優勢)：完美的夢想與動能結合，說得到，做得到。",
        advices: "• A. 防止「意義感燃燒殆盡」 (針對 O 型)：容易忽略自己的身心界限，請加入「刻意留白」休假保養制度。\n• B. 審視「潛在的操控性」 (針對 C 型)：導航太明確容易強行將他人納入你的軌道，練習容忍人際中的混沌。\n• C. 深化「脆弱的展示」 (針對 S 型)：偶爾向信任夥伴分享「我其實現在也很累/迷茫」，建立人性化的靈魂共鳴。\n• D. 定期校準羅盤 (針對 C-V 軸)：每半年重新問自己「這真的是我現階段最想抵達的港口嗎？」，敢於在海上轉彎。",
        peers: "與 「謹慎守成者 (SREC)」 或 「平穩漂浮者 (SREV)」 同行。SREV 的鬆弛感有助於你卸下過重的使命防護面具。",
        quote: "你所展現的狀態，是許多個案與探索者夢寐以求的彼岸。但請記得，航海的目的不是證明自己能完美航行，而是為了「體驗大海」。偶爾允許自己隨浪而行。"
      },
      "SPOV": {
        name: "理想遠征者",
        desc: "「理想遠征者」是一種充滿張力的擴張性狀態。你擁有「穩定的內核（S）」與「極致的向外利他投射（O）」，對自己有高度的掌控力（P），但對「具體目標」採取開放探索的彈性態度（V）。",
        state: "這是一種「無邊界的戰略拓荒」生命狀態。\n• 你的生命能量來自於自我與理想的共融。你像是一位航海家，知道船隻穩固（S）、動力充足（P），也明確知道要向外航行、服務世人（O），至於這條航線最後抵達的是哪一個具體島嶼，你並不設限（V）。\n• 這種「模糊性」並非沒有規劃，而是給予了你極大的戰略彈性，能在動盪的生態中提出跳脫框架、解決核心問題的方案。",
        strengths: "• 極強的戰略遠見：不看眼前蠅頭小利，而著眼長遠的社群生態與未來，視野極度開闊。\n• 強大的韌性與包容度：因為內核穩固且不執著於單一KPI，在劇烈變動的環境中適應力極強。\n• 具備超凡感召力：以「為理想而戰」的宏大姿態吸引志同道合者，容易形成高凝聚力的價值社群。",
        advices: "• A. 將「願景」轉化為「里程碑」：你的宏大目標容易讓團隊夥伴因缺乏精確指針而迷茫，請嘗試設定階段性的清晰目標(C)。\n• B. 警惕「過度擴張」的幻覺：不要以為所有阻礙都能光靠意志克服，定期盤點實際資源與基石。\n• C. 承擔不確定性的沉沒成本：停下來多與夥伴溝通遠景，消除團隊對未來不確定性的焦慮。",
        peers: "與 「謹慎守成者 (SREC)」 同行：SPOV 負責「遠征」，SREC 負責「留守與運營」，確保夢想不會因缺乏現實基礎而中斷。",
        quote: "你是文明的拓荒者。你航行的不僅僅是一條路，而是一場關於「可能性的測試」。只要你能偶爾回到港口，看看那些守護著你的結構，你的遠征將不僅是個人傳奇，更將成為留給世界的地圖。"
      },
      "SPEC": {
        name: "戰略領袖",
        desc: "「戰略領袖」代表一種極為冷靜、高效且目標導向的狀態。你如同精密的棋手，不為感性感傷所困，以精準的邏輯、自我價值的最大化與高度控制力，在人生的棋盤上強勢推進。",
        state: "這是一種「智性且有序」的佈局者生命狀態。\n• 你的內心是一台經過高度校準的精密機器。能將過去的所有輸贏與經驗（S）總結出高效策略。\n• 動力核心聚焦於自身優勢最大化、競爭力與效率提升（E）。採取高能動性（P）與無比清晰的目標導航（C），看重可被量化的卓越與資源配置，精準避開感性羈絆帶來的隱形成本。",
        strengths: "• 極致的理性能量：在危機和混亂中，總能第一時間冷靜拆解結構，抓到核心痛點。\n• 高效率的目標達成力：不說空話只談路徑，能以最少的資源與成本、在最短時間內達成任務。\n• 自律與一致性：溝通成本極低，邏輯清晰、標準明確，在專業領域極易建立卓越聲望。",
        advices: "• A. 練習「利他紅利」 (針對 E 的修正)：「人際信任」是無法直接計算的複利資產。試著加入「情感折算」，以「長線共贏」取代短線精算。\n• B. 覺察「冷漠」帶來的視盲：目標感太強（C）容易忽略部屬和親人情緒，多問「你的感受如何？」彌補死角。\n• C. 釋放權力，容忍瑕疵：真正的領袖在於「賦能」，容忍別人用非你設定的路徑達成目標。\n• D. 引入「靈魂反思」：每個月問自己「除了目標達成，這對我個人的生命意義是什麼？」避免成功後的空虛。",
        peers: "適合與 「隨緣觀察者 (SROV)」 同行，SROV 是你的「冷卻系統」，在你過熱時能給予情緒與人性的緩解。",
        quote: "你是推動現實世界前進的引擎。只要你能將那精密的計算器，裝上共情與意義的插件，你將不僅僅是達成目標的人，還會是定義未來遊戲規則的人。"
      },
      "SPEV": {
        name: "個人開拓者",
        desc: "「個人開拓者」處於一種極具行動力與自我整合力，但因目標模糊且偏向利己，呈現出「不斷自我重塑、卻找不到固定終點」的孤獨探索期。",
        state: "這是一種「以自我為圓心的游牧」生命狀態。\n• 你的內核強大，對過去經歷整合良好（S），擁有極佳行動力（P）。\n• 你的動力源自「我想要什麼/我感覺如何」（E），然而這種自我需求又是流動多變的（V）。這使你在職場上呈現跳躍式特徵，對新領域極具開拓熱情，但新鮮感過後或自我需求轉移後，會立刻抽身而去，像不願受約束的自由工作者。",
        strengths: "• 無與倫比的行動勇氣：想做就做、不依賴詳細規劃，是極佳的開拓冒險家。\n• 真實的自我覺察：對自己的慾望非常誠實，絕不為了迎合世俗期待而委屈委協，具野性魅力。\n• 豐富多樣的生命體驗：因為沒有固定航道，像海綿一樣吸收各種技能，人生故事與創意極豐。",
        advices: "• A. 練習「深度扎根」 (針對 V 的修正)：設定長期目標不代表失去自由，而是讓能量產生「複利」。強迫自己把項目完成到「專業級」。\n• B. 轉「自我中心」為「自我實現」 (針對 E )：問自己「五年後的我，會感謝現在我做的這個決定嗎？」拉長思考軸線。\n• C. 尋求結構夥伴互補：與擅長「經營、維護與規劃」的夥伴合作，你專注於「從無到有的創造」。\n• D. 建立習慣儀式感：利用規律的日誌或週復盤建立連續性，避免隨風漂泊產生的空虛感。",
        peers: "適合與 「睿智導師 (SROC)」 同行：導師能引導你將碎片化的體驗串聯，看到生命的連續軌跡。",
        quote: "你的生命是一間前衛的實驗室。每一次遷徙都在豐富人類行為的邊界。只要你學會偶爾停下來收集開拓的果實，你將不只是過客，而是具開創性的思想領袖。"
      },
      "SROC": {
        name: "睿智導師",
        desc: "「睿智導師」代表了一種極其成熟、溫暖且圓滿的生命狀態。你將生命的重心從個人的戰術成就，擴展到對整體環境的哺育、傳承與賦能。",
        state: "這是一種「內化後的寧靜」生命狀態。\n• 你經歷過風浪，完美整合了過往（S），擁有穩定行動力（P/R），但不再需要透過對外征服或精算來證明自己。\n• 你將能量聚焦於「利他服務」（O），且對人生終極方向（C）有著超越個人成就的深刻洞察。你擁有讓賢與托舉後輩的智慧，不爭奪聚光燈，光芒卻自然圍繞。",
        strengths: "• 無私的賦能者：樂意無保留地傾注資源、人脈、經驗，陪伴提攜後輩成長，極具領袖魅力。\n• 深邃的洞察力：把路走通過的人，能用極其簡練的話語點破複雜困局，帶給周邊人無比的安心感。\n• 強大的包容性：看過人性高低，豁達不評判，能接納他人的失敗與脆弱。",
        advices: "• A. 警惕「經驗的慣性」 (針對 S 軸過度)：智慧來自過去，但未來是新的。面對新世代，多嘗試「傾聽而不給建議」，單純陪伴。\n• B. 主動暴露「當下的困惑」：太睿智完美會使人不敢靠近，展現自己對新科技或新事物的無知，能縮短距離感。\n• C. 建立「非傳承式」社交：不要只待在需要你指導的圈子，尋找同等階、能挑戰你並給你新刺激的朋友。\n• D. 傳承「思維過程」而非「標準答案」：分享你當年如何犯錯、如何決策的掙扎，讓後輩獲得真正的智慧結晶。",
        peers: "適合與 「沉思療癒者 (FROC)」 同行，兩者能在「傳承與自我療癒」中形成絕佳的能量互補。",
        quote: "你是文明的火炬手。你的存在，讓世界少了一點迷茫，多了一點溫度。只要你持續對這個變動的世界保持好奇，你的智慧就永遠不會過時，反而隨著時間愈發醇厚。"
      },
      "SROV": {
        name: "隨緣觀察者",
        desc: "「隨緣觀察者」是一種充滿禪意與極致「鬆弛感」的生命狀態。你擁有強大的自我整合力（S）與行動力，心懷大局（O），但選擇不被狹隘的指標綁架，保持一種開闊流動的觀察視角（V）。",
        state: "這是一種「參與而不執著」的生命狀態。\n• 你並非懶散，相反地你具備極強實力，只是看透了「過度強求」帶來的反噬。\n• 你像是一條寬廣、清澈的河流，能承載萬物（O），能順勢避開障礙（P/R），但不急著奔向大海，而是享受沿途風景。不試圖控制他人或關係，是極佳的傾聽者。",
        strengths: "• 真正的心理自由：不受具體KPI或目標綁架，在高度焦慮的現代社會中顯得異常罕見且具療癒力。\n• 透徹的旁觀智慧：不執著於自身私利或單次勝負，總能提供極其客觀、順應自然規律的關鍵洞見。\n• 低耗能人際連結：不給人壓力、不需偽裝。是身邊朋友極佳的「能量充電站」。",
        advices: "• A. 警惕「過度抽離」的虛無感：隨緣容易滑向消極冷漠。當發現自己對任何事都無感時，請嘗試為一件生活小事投入情感。\n• B. 偶爾「主動出擊」：有些機會稍縱即逝。在冷靜觀察之餘，嘗試擔任一次「發起者」，將洞見轉化為群體影響力。\n• C. 確保「流動」不變成「漂泊」：確保生活中有幾個恆定的錨點（如親密關係、健康習慣），避免生活失去地基。",
        peers: "是 「戰略領袖 (SPEC)」 與 「理想遠征者 (SPOV)」 的極佳同行者，擔任他們的冷卻系統，帶給他們「過程即意義」的哲學慰藉。",
        quote: "你是這場人生大戲中最享受表演的觀眾。你的存在讓這場戲變得更溫暖、更具哲學深度。保持你的鬆弛，適時遞上溫暖。"
      },
      "SREC": {
        name: "謹慎守成者",
        desc: "「謹慎守成者」展現了一種高度完善的「個人護城河」狀態。你深知資源得來不易，將重心放在守護成果、精確防禦與穩健增長上。你是社會與組織中穩健、最靠得住的基石。",
        state: "這是一種「防禦性強的進取」生命狀態。\n• 你對過去的失敗有極強的復盤能力（S），做決定時優先防範重蹈覆轍。\n• 對自我邊界與利益（E）敏感，但非貪婪，而是對生存安全的高度捍衛。採取高度能動性（P/R），追求可控、低風險、回報確定的成功（C）。人生像一座精密防範的城堡。",
        strengths: "• 極致的風險管理能力：在變動頻繁的時代始終保持穩定、止損、保留實力，是驚人的倖存者。\n• 高品質的執行細節：不打無準備之仗，對細節嚴謹負責，是團隊不可或缺的堅實靠山。\n• 務實的理性與清醒：不沉溺不切實際的幻想，面對外界誘惑能保持清醒大腦，不衝動行事。",
        advices: "• A. 警惕「過度防禦」導致的萎縮：因為害怕變數而拒絕所有機會。請每年為自己留出一個「風險額度」去小冒險。\n• B. 擴張「利他」的邊界：守成力量目前僅服務於自己（E），試著保護身邊的人，這會幫你帶來更多外界支持。\n• C. 打破「控制幻想」：生命總有無法掌控的時刻，練習在小事上放手、容忍混亂，這是從小守成者跨越到大格局領袖的關鍵。",
        peers: "與 「理想遠征者 (SPOV)」 或 「戰略領袖 (SPEC)」 互補，擔任 SPOV 的「軍需官」，確保夢想可以落地維運。",
        quote: "你是歷史與結構的守護神。沒有你們，繁榮將無法延續。只要你們能偶爾打開大門，讓外面的陽光與變數照亮堡壘，人生將從穩健昇華為恆久。"
      },
      "SREV": {
        name: "平穩漂浮者",
        desc: "「平穩漂浮者」代表一種在舒適圈內安逸流動的狀態。你不執著於追求宏大目標，與世無爭、低壓力，極度看重個人生活的舒適度，展現了一種「自我守衡」的自在哲學。",
        state: "這是一種「極致的適應性」與「歲月靜好」生命狀態。\n• 你處理好了過去的糾結（S），對當下生活的瑣事有足夠掌控力（P/R）。\n• 你看重個人舒適與私人生活（E），只要環境不發生劇烈震盪，你就樂意維持安逸。缺乏宏大理想，但生活品質佳，這是一種「低干擾、低耗能」的平穩生存模型。",
        strengths: "• 極佳的「心理防禦力」：不容易被社會集體焦慮感染，是環境中的壓力緩衝帶，帶給周邊人無比的放鬆感。\n• 生活細節的品味者：非常懂得如何過日子，享受當下的寧靜與小確幸，有質樸的幸福感。\n• 穩定可靠的基層支柱：給予具體任務能不帶野心地踏實執行，不愛勾心鬥角，是極佳的合作對象。",
        advices: "• A. 引入「微目標」：設定體驗性目標（如每年學一個非工作技能），防止陷入「慣性癱瘓」，增加生活層次。\n• B. 覺察「舒適」背後的逃避：平穩有時是為了遮蔽對未來的恐懼，深度盤點未來十年，確保安逸是主動選擇而非逃避。\n• C. 增加「社會連結」的密度：將部分精力投入服務他人(O)，能帶來超越安逸的深刻滿足，提升生活豐盈度。",
        peers: "適合與 「睿智導師 (SROC)」 同行：導師能引導你從「無目的的漂浮」轉向「隨緣的耕耘」。",
        quote: "你不需要把忙碌當作人生意義。能像你一樣享受一整天的平靜而不感到罪惡，這本身就是極大的主動權。守護好你的平靜，再多探索一點點世界的廣度。"
      },
      "FPOC": {
        name: "熱血衝刺者",
        desc: "「熱血衝刺者」呈現一種「燃燒殆盡式」的高效能狀態。你試圖用「絕對清晰的目標（C）」與「極致的行動力（P）」來填補內心深處因「自我斷裂與創傷（F）」產生的巨大虛無感，並透過向外利他服務（O）尋求肯定。",
        state: "這是一種「代償性極致化」的奔跑生命狀態。\n• 與理想遠征者不同，你的內核是破碎不穩固的（F）。你的熱血並非源於豐盈，而是對「靜止與空虛」的極度恐懼。\n• 你不能停下來，一旦靜止就害怕墜入內心無法癒合的深淵，因此你全力奔跑。在達成目標的瞬間感到短暫勝利，隨後空虛感襲來，迫使你立刻投身下一個目標，形成典型 FPOC 循環。",
        strengths: "• 極致的「生存韌性」：能忍受常人無法想像的重壓、委屈與挫折，工作與利他付出是你的避風港。\n• 強大的目標與執行力：近乎完美地拆解與執行任務，不允許自己失敗，是團隊最放心的執行戰將。\n• 令人動容的過度付出：常常給予他人比需求更多的幫助與溫暖，不惜燃燒自我來爭取連結。",
        advices: "• A. 練習「目標歸零」：每週留出一段真空時間，不設任何KPI，單純去散步、呼吸，感受當下的存在而非成就。\n• B. 辨識「過度責任感」的陷阱：覺得「我不做天就會塌下來」是種防禦。學會拒絕與授權，將心力留給內在破碎（F）的修復。\n• C. 尋求「非績效連結」：建立不談工作、只講日常感受的純粹友誼。在不需要衝刺的地方練習示弱。\n• D. 將「追求結果」轉為「關懷過程」：專注於助人過程中與對方的靈魂連結，而不是「這個案是否結案了」的指標。",
        peers: "與 「平穩漂浮者 (SREV)」 同行，SREV 的無壓鬆弛能提醒你：慢下來，世界真的不會毀滅。",
        quote: "熱血的衝刺者，你跑得夠久、夠快了。你不需要再用下一個目標來證明你的價值，因為早在你出發的那一刻，你就已經完整且值得被愛。停下來，欣賞你自己留下的足跡。"
      },
      "FPOV": {
        name: "流浪的救援者",
        desc: "「流浪的救援者」擁有一顆極度渴望奉獻的心（O），但由於缺乏穩固的內在核心（F）與清晰的方向導航（V），呈現出衝動助人、迷惘漂泊且極易職業倦怠的救援狀態。",
        state: "這是一種「透過救贖他人來尋找北極星」的生命狀態。\n• 你的能量主動且敏銳（P），一看到苦難便忍不住衝上去救援。然而因為缺乏長期戰略規劃（V）與整合自我（F），你的行動常帶有隨機性。\n• 你像一個沒有地圖的救護車。潛意識裡，你希望透過把別人救起來，來向自己證明「我的靈魂也是完整的」。",
        strengths: "• 無差別的博愛主義：對他人的痛苦有著天然的同情與敏感，付出不計名利，極具人性光輝。\n• 極強的共情共鳴：因為自己受過傷（F），能真正蹲下來與最受苦、最難靠近的群體平等共處與對話。",
        advices: "• A. 將「衝動」轉為「觀察」：想立刻介入時強迫自己停下來，思考對方需要你的「拯救行動」還是僅僅需要你的「傾聽陪伴」？\n• B. 建立「服務邊界」：承認陪伴與助人是有極限的。告訴自己「我只能陪他走到這裡，接下來的路是他自己的。」\n• C. 尋找「願景 (V) 的雛形」：寫下三個你心目中理想世界的樣貌，讓你的救援行動在同一個願景鏈條下累積，不再亂槍打鳥。\n• D. 承認內在的破碎 (F)：你不需要假裝自己是全能的拯救者。在他人面前適度展現人性與脆弱，反而能建立更深連結。",
        peers: "與 「戰略領袖 (SPEC)」 同行，SPEC 的框架與邏輯能幫你將「衝動救火」轉換為「結構性服務」，保護能量不耗盡。",
        quote: "你衝動是因為你愛這世界。只要你願意為那份流浪的善意加上一個「錨」，你將從一位疲憊的消防員，進化為能帶領眾人走出黑夜的火炬手。"
      },
      "FPEC": {
        name: "逃避奔跑者",
        desc: "「逃避奔跑者」體現了一種高功能焦慮狀態。你內心深處有一個巨大的創傷斷層（F），為了不看見它，你唯一的生存策略就是「不停地設定目標（C）並瘋狂前進（P）」，同時極端關注自我利益（E）來維持動力。",
        state: "這是一種「透過移動來建立安全感」的生命狀態。\n• 與機械生存者不同，你是有熱度甚至焦躁的。你害怕停下來會被迫面對破碎與孤獨（F），所以瘋狂跑跳槽、考證照、賺快錢、瘋狂旅行。\n• 自我中心（E）在於你極度敏感於任何會阻礙你前進的事。你害怕與人建立過深的親密連結，因為那意味著要「停下來」和「磨合」，對你來說這等於逼你直面內心廢墟。",
        strengths: "• 即時推進力強：設定具體短期目標時具有超高執行效率，能快速獲得短期成就。\n• 高功能適應性：在快節奏、不斷變革、競爭激烈的環境中，能依靠奔跑慣性表現得極具生產力。",
        advices: "• A. 執行「原地沉澱」法：嘗試在一個目標達成後，強迫自己休息一週。體驗那種無聊與焦慮，在無聊深處療癒自我。\n• B. 辨識「逃避性目標」：檢視你的待辦清單，哪些是真正熱愛的？哪些只是為了讓自己「顯得很忙」而設立的假目標？\n• C. 建立「深耕型」關係：試著與一兩個重要的人建立長期友誼/伴侶關係，停止逃跑，在矛盾磨合中修復自我斷層。\n• D. 轉向內在挖掘：將你強大的行動力（P），轉移部分到心理諮商、靈性或深層自我對話上。",
        peers: "與 「睿智導師 (SROC)」 同行，導師能溫和地戳破你「你究竟是在追夢，還是在逃避昨天的夢魘？」的逃避機制。",
        quote: "你跑得那麼快，是因為怕後面的陰影追上你。但請記住，陰影之所以存在，是因為你一直在背對著陽光。轉過身，擁抱那道光，你就不再需要奔跑了。"
      },
      "FPEV": {
        name: "迷惘探索者",
        desc: "「迷惘探索者」的核心焦慮在於「根本不知道該往哪裡跑」的虛無感。你內在有破碎與不安（F），擁有極強的主動行動力（P），極度關心自身感受（E），但因為缺乏方向感（V），呈現出多而不精的漂流狀態。",
        state: "這是一種「在碎片中尋找北極星」的生命狀態。\n• 你缺乏清晰的終點，行動力像一隻在迷霧中高速飛行卻沒有導航的候鳥。\n• 你常問「這能解決我的問題嗎？」但苦無答案。人生充滿了換跑道、學新技能、參加心靈團體，永遠停留在探索階段，不敢深度投入。因為深度投入意味著要承擔失敗的風險，所以你選擇不斷切換賽道來逃避實質考驗。",
        strengths: "• 極佳的嘗試勇氣：好奇心重、敢於體驗不同的生活型態、學習不同技能，是不受框架限制的實驗家。\n• 敏銳的自我覺察力：對個人感受和利益極度敏感，對體制與虛偽目標有著天然的警惕。",
        advices: "• A. 練習「停止探索、強制停留」：在接下來三個月內不更換任何主要目標，將手頭專案執行到底，強迫自己面對停留時的焦慮。\n• B. 將「探索」轉為「敘事」：整理你過去換過的跑道，找出其中重複出現的潛在主題，那才是你願景（V）的雛形。\n• C. 尋找「穩定的錨」：找一位生活極規律、目標清晰的人，參與對方的生活節奏，藉由模仿外界的穩定來調校內在。\n• D. 擁抱「不完美」的結束：不要為了逃避失敗而永遠停留在草稿和準備階段，不完美的成品也比完美的想像有價值。",
        peers: "需要與 「使命舵手 (SPOC)」 同行，SPOC 能幫你將瑣碎的探索拼湊成一條有意義的連貫路徑。",
        quote: "你每一次的嘗試都沒有浪費，它們其實都是你拼湊自我地圖的碎片。只要你願意停下那高速旋轉的腳步，低下頭看看腳下的腳印，你會發現道路其實一直都在。"
      },
      "FROC": {
        name: "沉思療癒者",
        desc: "「沉思療癒者」體現了一種充滿建設性、主動（P）且外向利他（O）的自我建構。你內在有破碎或創傷未整合（F），但你拒絕沉淪，選擇透過為他人提供價值（O）與設定極清晰的目標（C）來獲取生活的掌控感。",
        state: "這是一種「代償性建構」的自強生命狀態。\n• 你不願讓自己墜入混亂深淵，因此將「療癒自己」這件事「專案化」。\n• 你像是在強風中修補房子的工匠。雖然內心牆壁仍有裂縫（F），但你憑著堅韌毅力將外牆修飾得井井有條、目標明確（C），藉由利他行為（O）獲得外界肯定與存在感，並以此暗示自己「我正在變好」。",
        strengths: "• 強大的自我修復紀律：面對破碎不墮落逃避，維持極高道德紀律與社會功能，在痛苦中創造價值。\n• 兼具深度與厚度的指導力：因曾體驗過破碎黑暗，給予他人指引時話語帶有厚度與實踐溫度，而非高高在上。\n• 社會價值轉化率極高：在慈善、教育、社工、諮商領域往往能產出極高品質的實質貢獻。",
        advices: "• A. 放下「績效導向」的療癒：不要把療癒當成KPI來管理。給自己留出毫無產出的留白時光，容忍不完美的自己。\n• B. 建立脆弱的緩衝區：找一段不需要你提供任何價值、不需要你拯救他人的關係，在裡面單純存在、展現破碎（F）。\n• C. 轉「清晰(C)」為「接納(S)」：把關注點從「為生活增添什麼指標」轉為「釋放與接納了過去的什麼遺憾」。",
        peers: "與 「睿智導師 (SROC)」 同行：導師能引導你理解，真正的完整不是靠指標堆疊，而是靠與過去和解而來。",
        quote: "你是生命荒野中的建築師。你的努力讓你在風雨中屹立不搖。只要你逐漸減少對外牆的修繕，轉向修補地基與過去和解，你將發現你建立的不再是避難所，而是溫暖的家。"
      },
      "FROV": {
        name: "迷惘奉獻者",
        desc: "「迷惘奉獻者」是一種充滿慈悲但同時極度耗能的狀態。你內心有創傷未整合（F），擁有一顆熱血奉獻、向外奉獻的心（O），並具備強大主動性（P），但因缺乏清晰目標與邊界（V），在奉獻中常感到漂泊與無力。",
        state: "這是一種「透過他人來拼湊自己」的生命狀態。\n• 你能感應到世界的痛苦，並因自身脆弱，產生「必須立刻做點什麼」的急迫感（P）。但缺乏導航（V），你不清楚這些努力最終對你和社會有何長遠結構性影響。\n• 你像是一盞在濃霧中劇烈閃爍的燈，極度努力地想照亮周圍，卻因為燈芯本身不穩固，每當救援/服務結束，內在迷惘與虛無感便會如潮水般湧回，意義在奉獻中迅速流失。",
        strengths: "• 極高社會參與度：只要有人呼救立刻出現，不計代價解決最底層、最瑣碎的燃眉之急。\n• 毫無保留的共情力：對他人的痛苦天然解碼，奉獻不帶一絲傲慢，是真正能蹲下來與受苦者平起平坐的溫暖存在。\n• 動人的純真：沒有武裝的赤子，單純相信「幫助別人就是好事」，給人極大感動。",
        advices: "• A. 將「奉獻行為」儀式化：固定服務時間和對象，限制無差別救助，幫自己建立心理邊界，防範被外界需求徹底吞噬。\n• B. 建立「自我關照清單」：每天問自己「今天我照顧到自己了嗎？」「如果我不去救別人，我今天能做什麼讓自己開心的事？」\n• C. 承認迷惘，停止假裝明確：練習坦白承認「我現在也很迷惘，但我願意陪你走這段路」，減輕緊繃的防衛。\n• D. 轉向「我成為什麼樣的人」：將焦點從做什麼(目標)轉向核心價值原則，以此脫離漫無目的的漂泊感。",
        peers: "與 「謹慎守成者 (SREC)」 同行：SREC 擅長風險管理與守成，能為你提供安全的容器，保護你不過度透支。",
        quote: "你是社會的隱形撫慰者。你不需要為了證明自己存在而燃燒殆盡。你的價值早已在善良中體現，現在你要學習的，是如何將那份流向他人的暖流，分出一部分來溫暖你自己。"
      },
      "FREC": {
        name: "機械生存者",
        desc: "「機械生存者」體現了一種透過「防禦性冷漠」來存活的防禦狀態。你內心深處的自我感是斷裂受創的（F），為了不讓生活崩潰，你將自己轉化為一台「執行指令的冷酷機器」，透過極利己的資源保護（E）與精確指標（C）維持表面運作。",
        state: "這是一種「將生命數據化與流程化」的防禦生命狀態。\n• 與主動選擇理性的戰略領袖不同，你是出於「不得不」而麻木。你對過去痛苦採取徹底切割防禦，放棄情緒反應（R），將所有工作與生存行動（P）轉為剛性邏輯流程。\n• 你活得像個計算器，死守儲蓄、職位，拒絕建立深交，防範再次淪為受害者。對周遭痛苦視而不見，因內在感受已被安全斷路器強行斷開。",
        strengths: "• 極致精確的執行力：能像機器般在規定的程序下高度重複工作，絕不出錯，效率驚人。\n• 極強的生存保護力：對危機極度警惕，精確控制個人風險，能在動盪大環境中保證自我的物質與崗位安全。",
        advices: "• A. 執行「情感復健」計劃：強迫自己每天感受一件小事（如喝咖啡時舌尖的溫度、聽音樂時的節奏），重啟荒廢的神經感知。\n• B. 轉「防禦」為「低風險參與」：在安全的人際關係中釋放一點點真實情緒。告訴別人「我今天有點累」，就是巨大的勝利。\n• C. 鬆動目標的剛性：把鋼條般的目標改為柔性指標（如今年撥一筆預算在放鬆的感官體驗上），找回人的尊嚴與彈性。\n• D. 尋求具備溫度的環境：尋找能容納你犯錯與無能、不會因失控而懲罰你的諮商或信任空間，卸下沈重的機器盔甲。",
        peers: "與 「隨緣觀察者 (SROV)」 同行，隨緣者不強求、不定義的鬆弛感，是喚醒你機械感知、讓大腦程序暫停的解毒劑。",
        quote: "你是在寒冬中為了取暖而不斷給自己結冰的人。只要你願意拆除那一層層為了安全而築起的盔甲，哪怕會有寒風吹進來，你也會重新感受到陽光的溫度。"
      },
      "FREV": {
        name: "徹底沉淪者",
        desc: "「徹底沉淪者」處於生命狀態底層、極度邊緣化與關機狀態。你內在完全破碎（F），對外部規則充滿抗拒與防禦（R），動力極度收縮在最原始生存本能（E），完全喪失了對未來的想像與方向感（V）。",
        state: "這是一種「生命荒原」與精神性流亡狀態。\n• 過去創傷巨大且未修復（F），你選擇徹底斷開與世界的連結。你的抗拒（R）是為了把世界與別人的關懷擋在外面，防範再次受傷。\n• 對未來沒有任何期待（V），活著只是物理上的生存。外界的建議與關懷，在你看來都是試圖掌控你的危險信號。",
        strengths: "• 本能性的生存韌性：在經歷了常人難以承受的靈魂破碎後，依然維持著最低限度的物理生存，這本身就是一種無比頑強、深沉的本能力量。",
        advices: "• A. 停止所有對自己的要求：不要逼自己立刻振作、找工作或設定目標。要求對你來說是進一步的撕裂。接受現狀的關機。\n• B. 尋找「生存遺留物」：在廢墟中尋找你唯一還存有連結的一點點事物（如餵街角的貓、看一片雲、喜歡的味道），那是你對世界的微弱觸角。\n• C. 接受物理性的在場：與安全不評判的陪伴者共處，不需要對話、不給建議，習慣「存在本身不會帶來威脅」。\n• D. 肯定最低限度的活著：能起床、能進食就是強大的勝利。承認生存本身即是意義，減少對自我無能的恐懼。",
        peers: "需要極具耐心、能長期忍受冷落與拒絕的 「睿智導師 (SROC)」 陪伴，導師的角色只是安靜守望、給予在場的力量。",
        quote: "你不是壞，也不是懶，你只是已經用盡全力，沒有力氣再承受任何一點「期待」的重量。在這徹底沉淪的深淵中，請容許自己休息，人間依然有一絲暖意與尊重等待你再次甦醒。"
      }
    };

    // App State
    let currentMode = 'quick'; // 'quick' or 'full'
    let currentPage = 0;
    const questionsPerPage = 6;
    let currentQuestions = [];
    let userAnswers = {}; // id -> score (1-7)
    
    // Core Scoring Metrics
    let scores = {
      S: 0, F: 0, P: 0, R: 0, O: 0, E: 0, C: 0, V: 0
    };
    let diagnosedProfile = "SPOC";

    // Initialize/Start Diagnostic
    function startTest(mode) {
      currentMode = mode;
      userAnswers = {};
      currentPage = 0;
      
      // Filter questions based on mode
      if (mode === 'quick') {
        currentQuestions = questionsList.filter(q => quickQuestionIDs.includes(q.id));
        document.getElementById('test-mode-badge').innerText = "快速體驗模式 (32題)";
      } else {
        currentQuestions = [...questionsList];
        document.getElementById('test-mode-badge').innerText = "深度診斷模式 (144題)";
      }

      // Hide welcome, show test page
      document.getElementById('welcome-screen').classList.add('hidden');
      document.getElementById('test-screen').classList.remove('hidden');
      document.getElementById('results-screen').classList.add('hidden');

      renderQuestions();
    }

    // Render questions for the current page
    function renderQuestions() {
      const container = document.getElementById('questions-container');
      container.innerHTML = '';

      const startIndex = currentPage * questionsPerPage;
      const endIndex = Math.min(startIndex + questionsPerPage, currentQuestions.length);
      const pageQuestions = currentQuestions.slice(startIndex, endIndex);

      // Group section title from first item of page
      if (pageQuestions.length > 0) {
        document.getElementById('current-section-title').innerText = pageQuestions[0].section;
      }

      pageQuestions.forEach((q, idx) => {
        const questionCard = document.createElement('div');
        questionCard.className = "bg-gray-900/45 border border-gray-800 p-5 rounded-2xl space-y-4 hover:border-gray-700 transition";
        
        // Header with Q number
        const header = document.createElement('div');
        header.className = "flex justify-between items-start text-xs text-gray-400";
        header.innerHTML = `<span>問題 ${startIndex + idx + 1} / ${currentQuestions.length}</span>`;
        questionCard.appendChild(header);

        // Text
        const text = document.createElement('p');
        text.className = "text-sm sm:text-base text-gray-100 font-medium leading-relaxed";
        text.innerText = q.text;
        questionCard.appendChild(text);

        // 1-7 Likert scale nodes
        const likertContainer = document.createElement('div');
        likertContainer.className = "flex flex-col space-y-2 pt-2";

        const nodeRow = document.createElement('div');
        nodeRow.className = "flex justify-between items-center w-full bg-slate-950/60 p-3 rounded-xl border border-gray-800/80 gap-1";

        const currentAnswer = userAnswers[q.id] || 0;

        for (let score = 1; score <= 7; score++) {
          const btn = document.createElement('button');
          btn.type = 'button';
          btn.onclick = () => selectAnswer(q.id, score);
          
          // Color coding for Likert nodes
          let activeClass = "bg-purple-600 text-white scale-110";
          let inactiveClass = "bg-gray-900 border border-gray-800 text-gray-400 hover:border-gray-600";
          
          if (score === currentAnswer) {
            btn.className = `w-8 h-8 rounded-full flex items-center justify-center text-xs font-bold transition-all ${activeClass}`;
          } else {
            btn.className = `w-8 h-8 rounded-full flex items-center justify-center text-xs font-medium transition-all ${inactiveClass}`;
          }
          btn.innerText = score;
          nodeRow.appendChild(btn);
        }

        likertContainer.appendChild(nodeRow);

        // Labels
        const labels = document.createElement('div');
        labels.className = "flex justify-between text-[10px] text-gray-500 px-1";
        labels.innerHTML = `<span>非常不同意 (1)</span><span>非常同意 (7)</span>`;
        likertContainer.appendChild(labels);

        questionCard.appendChild(likertContainer);
        container.appendChild(questionCard);
      });

      // Update Navigation
      document.getElementById('prev-btn').disabled = (currentPage === 0);
      if (currentPage === 0) {
        document.getElementById('prev-btn').classList.add('opacity-40', 'pointer-events-none');
      } else {
        document.getElementById('prev-btn').classList.remove('opacity-40', 'pointer-events-none');
      }

      const totalPages = Math.ceil(currentQuestions.length / questionsPerPage);
      document.getElementById('progress-text').innerText = `${currentPage + 1} / ${totalPages} 頁`;

      if (currentPage === totalPages - 1) {
        document.getElementById('next-btn').innerText = "提交並查看報告";
      } else {
        document.getElementById('next-btn').innerText = "下一頁";
      }

      // Update progress bar
      const progressPercent = ((currentPage) / totalPages) * 100;
      document.getElementById('progress-bar-fill').style.width = `${progressPercent}%`;

      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    // Capture User Answer
    function selectAnswer(questionId, score) {
      userAnswers[questionId] = score;
      // Re-render only to show active state instantly
      renderQuestions();
    }

    // Go to Prev Page
    function prevPage() {
      if (currentPage > 0) {
        currentPage--;
        renderQuestions();
      }
    }

    // Go to Next Page or Submit
    function nextPage() {
      // Validate all answers on current page are filled
      const startIndex = currentPage * questionsPerPage;
      const endIndex = Math.min(startIndex + questionsPerPage, currentQuestions.length);
      const pageQuestions = currentQuestions.slice(startIndex, endIndex);

      let unanswered = pageQuestions.filter(q => !userAnswers[q.id]);
      if (unanswered.length > 0) {
        showToast("請回答本頁的所有問題再前往下一步。");
        return;
      }

      const totalPages = Math.ceil(currentQuestions.length / questionsPerPage);
      if (currentPage < totalPages - 1) {
        currentPage++;
        renderQuestions();
      } else {
        submitTest();
      }
    }

    // Toast Notice Handler
    function showToast(msg) {
      const toast = document.getElementById('toast');
      document.getElementById('toast-msg').innerText = msg;
      toast.classList.remove('translate-y-10', 'opacity-0', 'pointer-events-none');
      
      setTimeout(() => {
        toast.classList.add('translate-y-10', 'opacity-0', 'pointer-events-none');
      }, 3000);
    }

    // Submit and calculate results
    function submitTest() {
      // Transition to Analyzing Screen
      document.getElementById('test-screen').classList.add('hidden');
      document.getElementById('analyzing-screen').classList.remove('hidden');

      setTimeout(() => {
        calculateDiagnostics();
        document.getElementById('analyzing-screen').classList.add('hidden');
        document.getElementById('results-screen').classList.remove('hidden');
        renderResultsDashboard();
      }, 2000); // 2 seconds analyzing animation
    }

    // Scoring calculation logic
    function calculateDiagnostics() {
      // Reset scores
      scores = { S: 0, F: 0, P: 0, R: 0, O: 0, E: 0, C: 0, V: 0 };
      let counts = { S: 0, F: 0, P: 0, R: 0, O: 0, E: 0, C: 0, V: 0 };

      // Process all answers
      currentQuestions.forEach(q => {
        const rawScore = userAnswers[q.id] || 4; // Default to neutral if somehow empty
        let processedScore = rawScore;

        if (q.isReverse) {
          processedScore = 8 - rawScore; // Reverse score
        }

        const dimension = q.dim;
        scores[dimension] += processedScore;
        counts[dimension]++;
      });

      // Calculate averages to maintain fairness
      const avg = {};
      Object.keys(scores).forEach(key => {
        avg[key] = counts[key] > 0 ? (scores[key] / counts[key]) : 4;
      });

      // Determine dimensions S vs F, P vs R, O vs E, C vs V
      const I = avg.S >= avg.F ? "S" : "F";
      const A = avg.P >= avg.R ? "P" : "R";
      const C = avg.O >= avg.E ? "O" : "E";
      const D = avg.C >= avg.V ? "C" : "V";

      diagnosedProfile = `${I}${A}${C}${D}`;
    }

    // Render results
    function renderResultsDashboard() {
      const profile = profilesDb[diagnosedProfile] || profilesDb["SPOC"];

      // Setup labels & text
      document.getElementById('res-formula-top').innerText = diagnosedProfile;
      document.getElementById('res-formula-card').innerText = diagnosedProfile;
      document.getElementById('res-archetype-name').innerText = profile.name;
      document.getElementById('res-short-description').innerText = profile.desc;
      
      document.getElementById('res-state-p').innerText = profile.state;
      document.getElementById('res-strengths-p').innerText = profile.strengths;
      document.getElementById('res-advices-p').innerText = profile.advices;
      
      if (profile.peers) {
        document.getElementById('res-peer-box').classList.remove('hidden');
        document.getElementById('res-peers-p').innerText = profile.peers;
      } else {
        document.getElementById('res-peer-box').classList.add('hidden');
      }
      
      document.getElementById('res-quote-span').innerText = profile.quote;

      // Render score progress gauges
      renderGauges();

      // Render custom SVG radar chart
      renderRadarChart();

      // Update Toggles in Calibrator panel to match current profile
      updateCalibrationToggles();

      // Generate Life Plan Dynamic Instruction content
      generateLifePlan();

      // Ensure report tab active on start
      switchTab('tab-report');
    }

    // Render HTML Gauge progress bars
    function renderGauges() {
      const parent = document.getElementById('dimensional-gauges');
      parent.innerHTML = '';

      // Dimensions mapping
      const dimMap = [
        { code: "I", leftName: "S 穩固", rightName: "F 破碎", leftKey: "S", rightKey: "F", color: "from-purple-500 to-indigo-500" },
        { code: "A", leftName: "P 主動", rightName: "R 防禦", leftKey: "P", rightKey: "R", color: "from-indigo-500 to-teal-500" },
        { code: "C", leftName: "O 利他", rightName: "E 自我", leftKey: "O", rightKey: "E", color: "from-teal-500 to-emerald-500" },
        { code: "D", leftName: "C 清晰", rightName: "V 模糊", leftKey: "C", rightKey: "V", color: "from-pink-500 to-purple-500" }
      ];

      dimMap.forEach(d => {
        // Calculate average
        let leftSum = 0, leftCount = 0;
        let rightSum = 0, rightCount = 0;

        currentQuestions.forEach(q => {
          if (q.dim === d.leftKey) { leftSum += (userAnswers[q.id] || 4); leftCount++; }
          if (q.dim === d.rightKey) { rightSum += (userAnswers[q.id] || 4); rightCount++; }
        });

        const leftAvg = leftCount > 0 ? (leftSum / leftCount) : 4;
        const rightAvg = rightCount > 0 ? (rightSum / rightCount) : 4;

        // Calculate ratio percentage (towards Right side vs Left)
        const total = leftAvg + rightAvg;
        const rightPercent = total > 0 ? Math.round((rightAvg / total) * 100) : 50;
        const leftPercent = 100 - rightPercent;

        const row = document.createElement('div');
        row.className = "space-y-1.5";
        row.innerHTML = `
          <div class="flex justify-between text-xs font-semibold">
            <span class="${leftPercent >= 50 ? 'text-gray-100 font-bold' : 'text-gray-500'}">${d.leftName} (${leftPercent}%)</span>
            <span class="${rightPercent > 50 ? 'text-gray-100 font-bold' : 'text-gray-500'}">${d.rightName} (${rightPercent}%)</span>
          </div>
          <div class="w-full bg-gray-900 h-2.5 rounded-full overflow-hidden border border-gray-800 relative flex">
            <!-- Left fill -->
            <div class="h-full bg-gradient-to-r ${d.color} transition-all duration-500" style="width: ${leftPercent}%"></div>
            <!-- Center dividing notch -->
            <div class="absolute left-1/2 top-0 bottom-0 w-0.5 bg-slate-950"></div>
          </div>
        `;
        parent.appendChild(row);
      });
    }

    // Draw dynamic interactive SVG Radar on the fly based on average values
    function renderRadarChart() {
      const container = document.getElementById('radar-container');
      container.innerHTML = '';

      // Determine score ratios for I, A, C, D
      const axesKeys = [
        { code: "I", pos: "S", neg: "F" },
        { code: "A", pos: "P", neg: "R" },
        { code: "C", pos: "O", neg: "E" },
        { code: "D", pos: "C", neg: "V" }
      ];

      const radius = 80;
      const center = 100;
      const scoresNorm = [];

      axesKeys.forEach(axis => {
        let posSum = 0, posCount = 0;
        let negSum = 0, negCount = 0;

        currentQuestions.forEach(q => {
          if (q.dim === axis.pos) { posSum += (userAnswers[q.id] || 4); posCount++; }
          if (q.dim === axis.neg) { negSum += (userAnswers[q.id] || 4); negCount++; }
        });

        const posAvg = posCount > 0 ? (posSum / posCount) : 4;
        const negAvg = negCount > 0 ? (negSum / negCount) : 4;

        // Normalize between 0.2 and 1.0 based on positive average vs negative average
        const ratio = posAvg / (posAvg + negAvg || 1);
        scoresNorm.push(Math.max(0.2, Math.min(1.0, ratio * 1.5))); // Amplified for beautiful radar display
      });

      // SVG dimensions 200x200
      // Calculate radar point coordinates (Top, Right, Bottom, Left)
      // Top: I, Right: A, Bottom: C, Left: D
      const points = [
        { x: center, y: center - (radius * scoresNorm[0]) }, // Top
        { x: center + (radius * scoresNorm[1]), y: center }, // Right
        { x: center, y: center + (radius * scoresNorm[2]) }, // Bottom
        { x: center - (radius * scoresNorm[3]), y: center }  // Left
      ];

      const pointsString = points.map(p => `${p.x},${p.y}`).join(' ');

      const svg = `
        <svg viewBox="0 0 200 200" class="w-full h-full drop-shadow-[0_0_12px_rgba(139,92,246,0.3)]">
          <!-- Radar Grid Rings -->
          <circle cx="100" cy="100" r="80" fill="none" stroke="#1F2937" stroke-width="1" />
          <circle cx="100" cy="100" r="55" fill="none" stroke="#111827" stroke-width="1" />
          <circle cx="100" cy="100" r="30" fill="none" stroke="#111827" stroke-width="1" />
          
          <!-- Axes -->
          <line x1="100" y1="20" x2="100" y2="180" stroke="#1F2937" stroke-width="1" />
          <line x1="20" y1="100" x2="180" y2="100" stroke="#1F2937" stroke-width="1" />
          
          <!-- Colored radar polygon -->
          <polygon points="${pointsString}" fill="rgba(139, 92, 246, 0.25)" stroke="#8B5CF6" stroke-width="2" />
          
          <!-- Radar points dots -->
          ${points.map((p, i) => `<circle cx="${p.x}" cy="${p.y}" r="4" fill="${i % 2 === 0 ? '#14B8A6' : '#EC4899'}" />`).join('')}
        </svg>
      `;
      container.innerHTML = svg;
    }

    // Switch Tabs in Results section
    function switchTab(tabId) {
      document.querySelectorAll('.tab-panel').forEach(panel => panel.classList.add('hidden'));
      document.querySelectorAll('[id^="tab-btn-"]').forEach(btn => {
        btn.classList.remove('border-purple-500', 'text-purple-400');
        btn.classList.add('text-gray-400');
      });

      document.getElementById(tabId).classList.remove('hidden');
      const activeBtnId = `tab-btn-${tabId.split('-')[1]}`;
      document.getElementById(activeBtnId).classList.add('border-purple-500', 'text-purple-400');
      document.getElementById(activeBtnId).classList.remove('text-gray-400');
    }

    // Calibrator Interactive panel code
    let calibratedProfile = ["S", "P", "O", "C"];

    function updateCalibrationToggles() {
      calibratedProfile = diagnosedProfile.split('');

      syncCalibratorUI();
    }

    function toggleCalibrate(dimension) {
      let idx = 0;
      let posChar = "S", negChar = "F";

      if (dimension === "I") { idx = 0; posChar = "S"; negChar = "F"; }
      else if (dimension === "A") { idx = 1; posChar = "P"; negChar = "R"; }
      else if (dimension === "C") { idx = 2; posChar = "O"; negChar = "E"; }
      else if (dimension === "D") { idx = 3; posChar = "C"; negChar = "V"; }

      // Toggle value
      calibratedProfile[idx] = (calibratedProfile[idx] === posChar) ? negChar : posChar;

      // Render new profile data on primary card instantly
      diagnosedProfile = calibratedProfile.join('');
      
      // Flash card effect to show changes
      const plate = document.getElementById('res-formula-card');
      plate.classList.add('scale-105');
      setTimeout(() => plate.classList.remove('scale-105'), 200);

      renderResultsDashboard();
      syncCalibratorUI();
    }

    function syncCalibratorUI() {
      // Toggle S vs F
      const isI_pos = (calibratedProfile[0] === "S");
      document.getElementById('toggle-i-label').innerText = isI_pos ? "穩固 Solid" : "破碎 Fragmented";
      updateToggleBtn("I", isI_pos, "bg-purple-600");

      // Toggle P vs R
      const isA_pos = (calibratedProfile[1] === "P");
      document.getElementById('toggle-a-label').innerText = isA_pos ? "主動 Proactive" : "防禦 Resistant";
      updateToggleBtn("A", isA_pos, "bg-indigo-600");

      // Toggle O vs E
      const isC_pos = (calibratedProfile[2] === "O");
      document.getElementById('toggle-c-label').innerText = isC_pos ? "利他 Outward" : "自我 Egocentric";
      updateToggleBtn("C", isC_pos, "bg-teal-600");

      // Toggle C vs V
      const isD_pos = (calibratedProfile[3] === "C");
      document.getElementById('toggle-d-label').innerText = isD_pos ? "清晰 Clear" : "模糊 Vague";
      updateToggleBtn("D", isD_pos, "bg-pink-600");
    }

    function updateToggleBtn(id, active, activeColorClass) {
      const btn = document.getElementById(`btn-toggle-${id}`);
      const ball = btn.querySelector('span');

      if (active) {
        btn.className = `relative inline-flex h-6 w-11 items-center rounded-full transition-colors ${activeColorClass}`;
        ball.className = "inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-6";
      } else {
        btn.className = "relative inline-flex h-6 w-11 items-center rounded-full transition-colors bg-gray-700";
        ball.className = "inline-block h-4 w-4 transform rounded-full bg-white transition-transform translate-x-1";
      }
    }

    // Generate dynamic customized Life Plan instructions
    function generateLifePlan() {
      document.getElementById('plan-code').innerText = diagnosedProfile;

      const hasClearDirection = diagnosedProfile.endsWith("C");
      const gapBox = document.getElementById('gap-instruction-box');
      const calBox = document.getElementById('calibration-instruction-box');

      // 1. Gaps Analysis
      if (hasClearDirection) {
        gapBox.innerHTML = `
          <p class="mb-2"><strong>你的方向感 (D) 為「清晰 (Clear)」狀態：</strong></p>
          <p>這代表你擁有一套明確的方向藍圖，知道自己要做什麼。此時你的意義斷層，通常在於<strong>「知行合一的深度」</strong>或<strong>「外部連結 (O) 與自我安全 (E) 的拉扯」</strong>。</p>
          <p class="mt-2 text-xs text-gray-400">🚨 注意點：不要讓高強度的目標感（C）變成控制身邊合作夥伴的工具，或者為了推進目標而忽略了內在未完全整合的脆弱創傷（F）。</p>
        `;
      } else {
        gapBox.innerHTML = `
          <p class="mb-2"><strong>你的方向感 (D) 為「模糊 (Vague)」狀態：</strong></p>
          <p>你正處於生命力量的<strong>「漂流期」</strong>。此時你的首要任務不是焦慮地去「強找一個宏大的目標」，而是<strong>尋找一個「錨點 (Anchor)」</strong>。</p>
          <p class="mt-2">你可以嘗試「人工輸入」幾項清晰的短期目標（C），去測試自我在這種清晰、穩定的框架下是否會感到安定，從而判斷你是否真的渴望建立長久的常規結構。</p>
        `;
      }

      // 2. Calibration Actions
      let calContent = "";
      
      // S vs F
      if (diagnosedProfile.startsWith("F")) {
        calContent += `<p class="mb-2">🔴 <strong>向「穩固 (S)」靠近：練習「故事的連續性」</strong><br>過去的創傷記憶可能不時被喚醒。不要試圖強行遺忘，每天抽 5 分鐘寫日記，試著給過去混亂、令你痛苦的經歷一個「意義標籤」。這能重構記憶，為當下注入連續性力量。</p>`;
      } else {
        calContent += `<p class="mb-2">🟢 <strong>鞏固「穩固 (S)」能量：適度分享脆弱</strong><br>因為你內核穩定，常被大家當靠山。請給自己建立一個「安全傾訴區」，主動與信任的人分享自己的疲憊或焦慮，讓你的連續性力量具備更自然的人性溫度。</p>`;
      }

      // O vs E
      const isOutward = diagnosedProfile.includes("O");
      if (isOutward) {
        calContent += `<p class="mb-2">🔵 <strong>避免「利他燃燒殆盡」：劃分身心留白界限</strong><br>因為你將能量完全釋放於社會責任與共用（O），有時會忽視自身身心與財務邊界。強迫自己每週「休假留白」，明白「我不插手也沒關係」是你目前的關鍵修行。</p>`;
      } else {
        calContent += `<p class="mb-2">🟡 <strong>嘗試「自我 (E)」向「利他 (O)」躍遷：小額善意投資</strong><br>試著把你擁有的優勢或高能動性能力（P），主動運用在小範圍服務某個同事、朋友或弱勢群體，不計名利地提供一次幫助，觀察自我充實感是否因此奇妙地上升。</p>`;
      }

      calBox.innerHTML = calContent;
    }

    // Reset whole Diagnostic App
    function resetDiagnostics() {
      userAnswers = {};
      currentPage = 0;
      diagnosedProfile = "SPOC";
      
      document.getElementById('welcome-screen').classList.remove('hidden');
      document.getElementById('test-screen').classList.add('hidden');
      document.getElementById('results-screen').classList.add('hidden');
      document.getElementById('analyzing-screen').classList.add('hidden');

      showToast("所有診斷記錄已清除，歡迎重新測驗。");
    }

    // Page Auto-load Initialization
    window.onload = function() {
      // Just double checks welcome active
      resetDiagnostics();
    };
  </script>
</body>
</html>
