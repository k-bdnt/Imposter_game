<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>لعبة من المحتال؟ 🎭 - النسخة المحدثة</title>
  <style>
    * { box-sizing: border-box; }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #f1f5f9;
      color: #0f172a;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      padding: 16px;
      padding-bottom: 90px;
      user-select: none;
      -webkit-user-select: none;
      overflow-x: hidden;
      position: relative;
    }

    /* أنيميشن عند الضغط على الشاشة */
    .tap-ripple {
      position: fixed;
      border-radius: 50%;
      background: rgba(124, 58, 237, 0.35);
      transform: scale(0);
      animation: rippleEffect 0.5s ease-out forwards;
      pointer-events: none;
      z-index: 9999;
    }

    @keyframes rippleEffect {
      to {
        transform: scale(3.5);
        opacity: 0;
      }
    }

    body::before, body::after {
      content: '';
      position: fixed;
      border-radius: 50%;
      background: rgba(124, 58, 237, 0.05);
      z-index: -1;
      transition: all 0.5s ease;
    }
    body::before { width: 350px; height: 350px; top: -100px; right: -50px; }
    body::after { width: 400px; height: 400px; bottom: -150px; left: -100px; }

    .card {
      background: #ffffff;
      border-radius: 28px;
      padding: 24px;
      width: 100%;
      max-width: 480px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.06);
      text-align: center;
      position: relative;
      transition: border-color 0.3s ease, box-shadow 0.3s ease, transform 0.2s ease;
      animation: popIn 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
      overflow: hidden;
    }

    @keyframes popIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }

    h1 {
      margin-top: 0;
      font-size: 26px;
      color: #0f172a;
      font-weight: 800;
    }

    /* تحسين مظهر خانة الصح Checkbox */
    input[type="checkbox"] {
      appearance: none;
      -webkit-appearance: none;
      width: 22px;
      height: 22px;
      border: 2px solid #cbd5e1;
      border-radius: 6px;
      outline: none;
      cursor: pointer;
      position: relative;
      background-color: #ffffff;
      transition: all 0.2s ease;
      flex-shrink: 0;
    }

    input[type="checkbox"]:checked {
      background-color: var(--player-dynamic-color, #7c3aed);
      border-color: var(--player-dynamic-color, #7c3aed);
    }

    input[type="checkbox"]:checked::after {
      content: '✓';
      position: absolute;
      color: white;
      font-size: 14px;
      font-weight: bold;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    .top-progress-bar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 20px;
      gap: 12px;
    }

    .progress-track {
      flex: 1;
      height: 8px;
      background: #e2e8f0;
      border-radius: 10px;
      overflow: hidden;
    }

    .progress-fill {
      height: 100%;
      width: 0%;
      background: var(--player-dynamic-color, #7c3aed);
      border-radius: 10px;
      transition: width 0.4s cubic-bezier(0.4, 0, 0.2, 1), background-color 0.3s ease;
    }

    .player-step-badge {
      background: #ffffff;
      color: #0f172a;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: bold;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
    }

    /* ========================================================= */
    /* تأثير قلب البطاقة 3D (3D Flip Card Effect) */
    /* ========================================================= */
    .flip-card-perspective {
      perspective: 1000px;
      width: 100%;
      min-height: 290px;
      margin: 10px 0;
    }

    .player-card-box {
      width: 100%;
      height: 100%;
      min-height: 290px;
      position: relative;
      transform-style: preserve-3d;
      transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
      cursor: pointer;
      touch-action: none;
    }

    .player-card-box.flipped {
      transform: rotateY(180deg);
    }

    .card-face {
      position: absolute;
      width: 100%;
      height: 100%;
      backface-visibility: hidden;
      -webkit-backface-visibility: hidden;
      border-radius: 28px;
      padding: 24px 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 12px;
      box-shadow: 0 14px 28px rgba(0, 0, 0, 0.12);
    }

    /* الوجه الأمامي */
    .card-front {
      background: var(--player-dynamic-color, #7c3aed);
      background-image: repeating-linear-gradient(45deg, rgba(255, 255, 255, 0.08) 0, rgba(255, 255, 255, 0.08) 10px, transparent 0, transparent 20px);
      color: #ffffff;
    }

    /* الوجه الخلفي (مطابق للون اللاعب مع تحسين التباين) */
    .card-back {
      background: var(--player-dynamic-color, #7c3aed);
      background-image: radial-gradient(circle, rgba(255,255,255,0.15) 0%, rgba(0,0,0,0.1) 100%);
      color: #ffffff;
      border: 3px solid rgba(255, 255, 255, 0.4);
      transform: rotateY(180deg);
    }

    .avatar-icon-box {
      width: 65px;
      height: 65px;
      background: rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 30px;
      backdrop-filter: blur(5px);
      pointer-events: none;
      transition: transform 0.3s ease;
    }

    .player-card-box:hover .avatar-icon-box { transform: scale(1.1) rotate(5deg); }

    .player-card-box h2 {
      margin: 0;
      font-size: 26px;
      font-weight: 800;
      pointer-events: none;
    }

    .click-icon-circle {
      width: 55px;
      height: 55px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.25);
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 24px;
      backdrop-filter: blur(5px);
      pointer-events: none;
      animation: bounce 1.5s infinite;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-6px); }
    }

    .secret-card-content {
      width: 100%;
      text-align: center;
    }

    .secret-card-content p {
      font-size: 24px;
      font-weight: 800;
      margin: 0;
      color: #ffffff !important;
      text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
      transition: color 0.3s ease;
    }

    .hint-badge {
      display: inline-block;
      margin-top: 8px;
      padding: 6px 14px;
      background: rgba(255, 255, 255, 0.9);
      color: #0f172a;
      border-radius: 12px;
      font-size: 13px;
      font-weight: bold;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .bottom-tabs {
      position: fixed;
      bottom: 12px; left: 50%;
      transform: translateX(-50%);
      width: 90%;
      max-width: 420px;
      background: rgba(255, 255, 255, 0.9);
      backdrop-filter: blur(10px);
      border: 1px solid #e2e8f0;
      border-radius: 30px;
      display: flex;
      justify-content: space-around;
      padding: 6px 10px;
      z-index: 100;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
    }

    .tab-btn {
      background: none;
      border: none;
      color: #64748b;
      font-size: 12px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 3px;
      padding: 6px 14px;
      cursor: pointer;
      border-radius: 20px;
      transition: all 0.2s ease;
    }

    .tab-btn.active {
      color: var(--player-dynamic-color, #7c3aed);
      background: #f1f5f9;
      font-weight: bold;
    }

    .tab-btn span { font-size: 18px; }
    .tab-content { display: none; }
    .tab-content.active { display: block; animation: fadeIn 0.3s ease; }

    @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }

    .section-box {
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      padding: 16px;
      border-radius: 20px;
      margin-bottom: 15px;
      text-align: right;
      width: 100%;
    }

    .section-box h3 {
      margin-top: 0;
      font-size: 15px;
      color: #0f172a;
      border-bottom: 1px solid #e2e8f0;
      padding-bottom: 8px;
    }

    /* ========================================================= */
    /* تحسينات تنسيق تبويبة التصنيفات Modern */
    /* ========================================================= */
    .categories-list-wrapper {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 10px;
    }

    .category-card-item {
      display: flex;
      align-items: center;
      justify-content: space-between;
      font-size: 14px;
      font-weight: 700;
      background: #ffffff;
      padding: 12px 16px;
      border-radius: 16px;
      border: 1px solid #e2e8f0;
      cursor: pointer;
      gap: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
      transition: all 0.2s ease;
    }

    .category-card-item:hover {
      border-color: var(--player-dynamic-color, #7c3aed);
      transform: translateY(-2px);
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.06);
    }

    .category-info {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .add-category-box {
      background: #ffffff;
      border: 1px dashed #cbd5e1;
      border-radius: 18px;
      padding: 16px;
      margin-top: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.02);
    }

    .add-category-box input[type="text"] {
      width: 100%;
      padding: 11px 14px;
      margin-bottom: 10px;
      border-radius: 12px;
      border: 1px solid #e2e8f0;
      background: #f8fafc;
      font-size: 13.5px;
      outline: none;
      transition: all 0.2s ease;
    }

    .add-category-box input[type="text"]:focus {
      border-color: var(--player-dynamic-color, #7c3aed);
      background: #ffffff;
      box-shadow: 0 0 0 3px rgba(124, 58, 237, 0.1);
    }

    .counter-control-group {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: #ffffff;
      padding: 10px 14px;
      border-radius: 14px;
      border: 1px solid #e2e8f0;
      margin-bottom: 12px;
    }

    .counter-btn-wrapper {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .btn-counter {
      width: 36px;
      height: 36px;
      border-radius: 10px;
      background: #f1f5f9;
      border: 1px solid #cbd5e1;
      color: #0f172a;
      font-size: 18px;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      margin: 0;
      padding: 0;
      transition: all 0.2s ease;
    }

    .btn-counter:active { transform: scale(0.9); background: #e2e8f0; }

    .counter-value {
      font-size: 16px;
      font-weight: bold;
      min-width: 24px;
      text-align: center;
    }

    #players-inputs-list {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 10px;
      width: 100%;
    }

    .player-row {
      display: flex;
      align-items: center;
      gap: 8px;
      background: #ffffff;
      padding: 8px 10px;
      border-radius: 16px;
      border: 1px solid #e2e8f0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.02);
      transition: all 0.2s ease;
      width: 100%;
      flex-wrap: nowrap;
    }

    .player-row:focus-within {
      border-color: #7c3aed;
      box-shadow: 0 4px 12px rgba(124, 58, 237, 0.1);
    }

    .player-number-badge {
      font-size: 12px;
      font-weight: 800;
      color: #64748b;
      background: #f1f5f9;
      width: 26px;
      height: 26px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }

    .player-row input[type="text"] {
      flex: 1;
      min-width: 0;
      padding: 8px 10px;
      border-radius: 10px;
      border: 1px solid #e2e8f0;
      background: #f8fafc;
      color: #0f172a;
      font-size: 14px;
      font-weight: bold;
      outline: none;
      transition: border-color 0.2s;
    }

    .player-row input[type="text"]:focus {
      border-color: #7c3aed;
      background: #ffffff;
    }

    .player-row input[type="color"] {
      border: none;
      width: 30px;
      height: 30px;
      border-radius: 50%;
      cursor: pointer;
      background: none;
      flex-shrink: 0;
      padding: 0;
    }

    .btn-delete-player {
      background: #fef2f2;
      color: #ef4444;
      border: 1px solid #fecaca;
      width: 30px;
      height: 30px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      font-weight: bold;
      font-size: 13px;
      margin: 0;
      padding: 0;
      flex-shrink: 0;
      transition: all 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    .btn-delete-player:hover {
      background: #ef4444;
      color: #ffffff;
      border-color: #ef4444;
      transform: scale(1.05) rotate(90deg);
    }

    .btn-delete-player:active {
      transform: scale(0.9);
    }

    .impostor-pills {
      display: flex;
      gap: 6px;
      margin-top: 8px;
      flex-wrap: wrap;
    }

    .impostor-pill {
      flex: 1 1 calc(50% - 6px);
      min-width: 90px;
      padding: 8px;
      border-radius: 12px;
      border: 1px solid #cbd5e1;
      background: #ffffff;
      font-size: 13px;
      font-weight: bold;
      cursor: pointer;
      text-align: center;
      transition: all 0.2s ease;
    }

    .impostor-pill.active {
      background: var(--player-dynamic-color, #7c3aed);
      color: #ffffff;
      border-color: var(--player-dynamic-color, #7c3aed);
      box-shadow: 0 4px 12px rgba(124, 58, 237, 0.2);
    }

    .checkbox-group, .options-group {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .checkbox-item {
      display: flex;
      align-items: center;
      justify-content: space-between;
      font-size: 13px;
      background: #ffffff;
      padding: 10px 12px;
      border-radius: 12px;
      border: 1px solid #f1f5f9;
      cursor: pointer;
      gap: 8px;
    }

    .btn-view-icon {
      background: #f1f5f9;
      color: #0f172a;
      border: 1px solid #cbd5e1;
      width: 34px;
      height: 34px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 16px;
      cursor: pointer;
      transition: all 0.2s ease;
      flex-shrink: 0;
      padding: 0;
      margin: 0;
    }

    .btn-view-icon:hover { 
      background: #e2e8f0; 
      color: var(--player-dynamic-color, #7c3aed);
      transform: scale(1.05);
    }

    button {
      border: none;
      padding: 14px;
      font-size: 15px;
      font-weight: bold;
      border-radius: 16px;
      cursor: pointer;
      margin-top: 10px;
      width: 100%;
      transition: all 0.2s ease;
    }

    button:active { transform: scale(0.98); }

    .btn-primary {
      background: var(--player-dynamic-color, #7c3aed);
      color: white;
      box-shadow: 0 4px 15px rgba(124, 58, 237, 0.3);
    }

    .btn-secondary { background: #10b981; color: white; }
    .btn-danger { background: #ef4444; color: white; }

    .hidden { display: none !important; }

    .multi-vote-card {
      background: #ffffff;
      border: 2px solid #e2e8f0;
      color: #0f172a;
      padding: 14px 16px;
      margin-top: 10px;
      border-radius: 16px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.25s ease;
    }

    .multi-vote-card.selected {
      border-color: var(--player-dynamic-color, #7c3aed);
      background: rgba(124, 58, 237, 0.08);
      transform: scale(1.01);
    }

    .checkbox-icon {
      width: 26px;
      height: 26px;
      border-radius: 8px;
      border: 2px solid #cbd5e1;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 14px;
      color: white;
      background: white;
      transition: all 0.2s ease;
    }

    .multi-vote-card.selected .checkbox-icon {
      background: var(--player-dynamic-color, #7c3aed);
      border-color: var(--player-dynamic-color, #7c3aed);
    }

    /* ========================================================= */
    /* تحسينات وتنسيقات صفحة النتائج الحديثة */
    /* ========================================================= */
    .reveal-cards-grid {
      display: flex;
      flex-direction: column;
      gap: 12px;
      margin: 16px 0;
    }

    .reveal-hero-card {
      position: relative;
      background: #ffffff;
      border-radius: 20px;
      padding: 16px 20px;
      display: flex;
      align-items: center;
      gap: 16px;
      border: 1px solid #e2e8f0;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.03);
      text-align: right;
      overflow: hidden;
      transition: transform 0.2s ease;
    }

    .reveal-hero-card:hover {
      transform: translateY(-2px);
    }

    .reveal-hero-card.word-card {
      border-right: 6px solid #10b981;
      background: linear-gradient(135deg, #ffffff 0%, #f0fdf4 100%);
    }

    .reveal-hero-card.impostor-card {
      border-right: 6px solid #ef4444;
      background: linear-gradient(135deg, #ffffff 0%, #fef2f2 100%);
    }

    .reveal-icon-circle {
      width: 48px;
      height: 48px;
      border-radius: 16px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 24px;
      flex-shrink: 0;
    }

    .word-card .reveal-icon-circle {
      background: #d1fae5;
      color: #059669;
    }

    .impostor-card .reveal-icon-circle {
      background: #fee2e2;
      color: #dc2626;
    }

    .reveal-content-info {
      flex: 1;
    }

    .reveal-label {
      font-size: 12px;
      font-weight: 700;
      color: #64748b;
      margin-bottom: 2px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .reveal-value {
      font-size: 20px;
      font-weight: 800;
      color: #0f172a;
      margin: 0;
    }

    .word-card .reveal-value { color: #059669; }
    .impostor-card .reveal-value { color: #dc2626; }

    /* التصويت والترتيب بصرياً */
    .results-ranking-box {
      margin-top: 20px;
      text-align: right;
    }

    .results-ranking-title {
      font-size: 15px;
      font-weight: 800;
      color: #0f172a;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .result-rank-card {
      display: flex;
      flex-direction: column;
      gap: 6px;
      padding: 14px;
      border-radius: 16px;
      background: #ffffff;
      border: 1px solid #e2e8f0;
      margin-bottom: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.02);
      transition: all 0.2s ease;
    }

    .result-rank-card.top-voted {
      border: 2px solid #ef4444;
      background: #fff5f5;
      box-shadow: 0 6px 16px rgba(239, 68, 68, 0.12);
      animation: pulseBorder 2s infinite ease-in-out;
    }

    @keyframes pulseBorder {
      0%, 100% { border-color: #ef4444; }
      50% { border-color: #f87171; }
    }

    .rank-card-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .rank-player-name {
      font-size: 15px;
      font-weight: 800;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .top-voted-badge {
      background: #ef4444;
      color: #ffffff;
      font-size: 11px;
      padding: 3px 8px;
      border-radius: 12px;
      font-weight: bold;
    }

    .rank-votes-count {
      font-size: 13px;
      font-weight: 800;
      color: #475569;
      background: #f1f5f9;
      padding: 4px 10px;
      border-radius: 20px;
    }

    .top-voted .rank-votes-count {
      background: #fee2e2;
      color: #991b1b;
    }

    .vote-bar-track {
      height: 6px;
      width: 100%;
      background: #f1f5f9;
      border-radius: 10px;
      overflow: hidden;
    }

    .vote-bar-fill {
      height: 100%;
      background: #94a3b8;
      border-radius: 10px;
      transition: width 0.6s cubic-bezier(0.4, 0, 0.2, 1);
    }

    .top-voted .vote-bar-fill {
      background: #ef4444;
    }

    .starter-player-banner {
      background: #ffffff;
      border: 2px dashed var(--starter-dynamic-color, #7c3aed);
      padding: 16px;
      border-radius: 18px;
      margin: 14px 0;
      animation: pulseBanner 1.5s infinite alternate;
    }

    @keyframes pulseBanner {
      from { transform: scale(0.99); }
      to { transform: scale(1.02); }
    }

    .wild-card {
      background: #fef3c7;
      border-right: 4px solid #f59e0b;
      padding: 14px;
      border-radius: 12px;
      margin: 14px 0;
      font-size: 14px;
      text-align: right;
      color: #78350f;
    }

    .timer-display {
      font-size: 38px;
      font-weight: bold;
      color: #dc2626;
      margin: 10px 0;
      font-family: monospace;
    }

    .modal-overlay {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(15, 23, 42, 0.6);
      backdrop-filter: blur(8px);
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 1000;
      padding: 20px;
      animation: fadeInModal 0.25s ease;
    }

    @keyframes fadeInModal {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .modal-content {
      background: #ffffff;
      border-radius: 24px;
      padding: 24px;
      width: 100%;
      max-width: 440px;
      text-align: right;
      max-height: 85vh;
      display: flex;
      flex-direction: column;
      box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
      animation: slideUpModal 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    @keyframes slideUpModal {
      from { opacity: 0; transform: translateY(20px) scale(0.95); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }

    .words-tags-container {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin: 14px 0;
      max-height: 260px;
      overflow-y: auto;
      padding: 10px;
      background: #f8fafc;
      border-radius: 14px;
      border: 1px solid #e2e8f0;
    }

    .word-tag {
      background: #ffffff;
      color: #0f172a;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: bold;
      display: flex;
      align-items: center;
      gap: 6px;
      border: 1px solid #cbd5e1;
      box-shadow: 0 2px 4px rgba(0,0,0,0.02);
    }

    .word-tag span { cursor: pointer; color: #ef4444; font-weight: bold; }
  </style>
</head>
<body>

  <div class="card" id="main-card">
    <h1>🎭 لعبة من المحتال؟</h1>

    <!-- 1. إعدادات اللعبة -->
    <div id="setup-step">
      
      <!-- تبويب 1: التصنيفات المنظمة والمرتبة -->
      <div id="tab-categories" class="tab-content active">
        <section class="section-box">
          <h3>📂 اختر تصنيفات الكلمات:</h3>
          <div id="categories-container" class="categories-list-wrapper"></div>
          
          <details style="margin-top:14px; font-size:13px;">
            <summary style="cursor:pointer; font-weight:bold; color:var(--player-dynamic-color, #7c3aed); padding:4px 0;">➕ إضافة تصنيف جديد</summary>
            <div class="add-category-box">
              <input type="text" id="new-cat-name" placeholder="اسم التصنيف الجديد (مثال: رياضات)">
              <input type="text" id="new-cat-words" placeholder="الكلمات مفرقة بـ فارزة (كرة القدم, كرة السلة)">
              <button class="btn-primary" style="margin-top:6px;" onclick="addCustomCategory()">حفظ التصنيف وإضافة الكلمات 💾</button>
            </div>
          </details>
        </section>
      </div>

      <!-- تبويب 2: اللاعبين -->
      <div id="tab-players" class="tab-content">
        <section class="section-box">
          <h3>👥 إعدادات اللاعبين والمحتالين:</h3>
          
          <div class="counter-control-group">
            <span style="font-weight:bold; font-size:14px;">عدد اللاعبين:</span>
            <div class="counter-btn-wrapper">
              <button class="btn-counter" onclick="changePlayerCount(-1)">-</button>
              <span id="players-count-display" class="counter-value">4</span>
              <button class="btn-counter" onclick="changePlayerCount(1)">+</button>
            </div>
          </div>

          <div id="players-inputs-list"></div>

          <div style="margin-top:14px;">
            <label style="font-weight:bold; font-size:14px; display:block; text-align:right;">عدد المحتالين:</label>
            <div class="impostor-pills">
              <div class="impostor-pill" onclick="setImpostorCount('random')" id="imp-pill-random">🎲 عشوائي</div>
              <div class="impostor-pill active" onclick="setImpostorCount('1')" id="imp-pill-1">1 محتال</div>
              <div class="impostor-pill" onclick="setImpostorCount('2')" id="imp-pill-2">2 محتالين</div>
              <div class="impostor-pill" onclick="setImpostorCount('3')" id="imp-pill-3">3 محتالين</div>
            </div>
          </div>
        </section>

        <section class="section-box">
          <h3>⭐ الأدوار الخاصة المتاحة:</h3>
          <div class="options-group">
            <div class="checkbox-item" onclick="toggleOption('role-detective')">
              <label for="role-detective">🔎 المحقق (يتعرف على بريء)</label>
              <input type="checkbox" id="role-detective" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('role-joker')">
              <label for="role-joker">🃏 المُضلل (يشوف كلمة مضللة)</label>
              <input type="checkbox" id="role-joker" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('role-seer')">
              <label for="role-seer">🧙‍♂️ الساحر / العرّاف (يكشف المحتال مباشرة)</label>
              <input type="checkbox" id="role-seer" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
          </div>
        </section>
      </div>

      <!-- تبويب 3: الخيارات والنقاط -->
      <div id="tab-options" class="tab-content">
        <section class="section-box">
          <h3>⚙ خيارات اللعبة:</h3>
          <div class="options-group">
            <div class="checkbox-item" onclick="toggleOption('opt-word-hint')">
              <label for="opt-word-hint">💡 إظهار تلميح خفيف يساعد في المعرفة</label>
              <input type="checkbox" id="opt-word-hint" onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-player-as-word')">
              <label for="opt-player-as-word">👤 إمكانية يكون اسم لاعب هو الكلمة السرية</label>
              <input type="checkbox" id="opt-player-as-word" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-enable-voting')">
              <label for="opt-enable-voting">🗳️ تفعيل التصويت السري</label>
              <input type="checkbox" id="opt-enable-voting" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-betting')">
              <label for="opt-betting">🎲 تفعيل نظام الرهانات</label>
              <input type="checkbox" id="opt-betting" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-impostor-friends')">
              <label for="opt-impostor-friends">🤝 وضع المحتالين الأصدقاء</label>
              <input type="checkbox" id="opt-impostor-friends" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-wildcard')">
              <label for="opt-wildcard">🃏 كروت الأحداث العشوائية</label>
              <input type="checkbox" id="opt-wildcard" checked onclick="event.stopPropagation(); saveOptionsToStorage();">
            </div>
            <div class="checkbox-item" onclick="toggleOption('opt-timer')">
              <label for="opt-timer">⏱️ مؤقت النقاش</label>
              <input type="checkbox" id="opt-timer" onchange="toggleTimerInput(); saveOptionsToStorage();" onclick="event.stopPropagation();">
            </div>

            <div id="timer-input-box" class="hidden" style="display:flex; justify-content:space-between; align-items:center; margin-top:5px;">
              <label>مدة المؤقت (دقائق):</label>
              <input type="number" id="timer-minutes" min="1" max="10" value="3" onchange="saveOptionsToStorage()" style="width:70px; text-align:center; padding:6px; border-radius:8px; border:1px solid #cbd5e1;">
            </div>
          </div>
        </section>

        <details class="section-box">
          <summary style="cursor:pointer; font-weight:bold;">🏆 جدول الترتيب والنقاط التراكمية</summary>
          <table style="width:100%; border-collapse:collapse; margin-top:10px; text-align:right; font-size:14px;">
            <thead>
              <tr style="border-bottom:1px solid #e2e8f0;"><th>اللاعب</th><th>النقاط</th></tr>
            </thead>
            <tbody id="scoreboard-body"></tbody>
          </table>
        </details>
      </div>

      <button class="btn-primary" onclick="startGame()" style="margin-top:15px;">ابدأ اللعبة 🚀</button>
    </div>

    <!-- 2. مرحلة كشف الأدوار (أنيميشن قلب البطاقة 3D) -->
    <div id="role-step" class="hidden">
      <div class="top-progress-bar">
        <div class="progress-track">
          <div id="progress-fill-bar" class="progress-fill"></div>
        </div>
        <div id="player-step-text" class="player-step-badge">لاعب 1 من 4</div>
      </div>

      <!-- حاوية ثلاثية الأبعاد لقلب البطاقة -->
      <div class="flip-card-perspective">
        <div id="main-player-card" class="player-card-box" 
             onpointerdown="startHold(event)" onpointerup="endHold(event)" onpointercancel="endHold(event)">
          
          <!-- الوجه الأمامي للبطاقة -->
          <div class="card-face card-front">
            <div class="avatar-icon-box">👤</div>
            <h2 id="card-player-name">لاعب 1</h2>
            <div id="click-icon" class="click-icon-circle">👆</div>
            <p id="click-hint-title" style="font-size:15px; font-weight:bold; margin:0; pointer-events:none;">اضغط مطولاً لكشف الكلمة</p>
            <p id="click-hint-sub" style="font-size:12px; opacity:0.8; margin-top:-8px; pointer-events:none;">تنقلب البطاقة وتختفي فور ترك الضغط</p>
          </div>

          <!-- الوجه الخلفي للبطاقة (ملون بنفس لون اللاعب بدلاً من الأبيض) -->
          <div class="card-face card-back">
            <div class="secret-card-content">
              <p id="secret-text"></p>
              <div id="secret-hint-badge" class="hint-badge hidden"></div>
              <small id="role-desc" style="display:block; margin-top:8px; color:rgba(255,255,255,0.9); font-weight:bold;"></small>

              <div id="bet-section" class="hidden" style="background:rgba(255, 255, 255, 0.2); backdrop-filter:blur(5px); padding:10px; border-radius:12px; margin-top:12px; pointer-events:auto;" onclick="event.stopPropagation();">
                <label style="font-size:12px; color:#ffffff; font-weight:bold; display:block; margin-bottom:4px;">🎲 اختار رهانك فـ هاد الجولة:</label>
                <select id="player-bet-select" style="width:100%; padding:6px; border-radius:8px; border:1px solid rgba(255,255,255,0.4); background:#ffffff; color:#0f172a; font-weight:bold;">
                  <option value="none">بدون رهان</option>
                  <option value="find_impostor">غادي نكتشف المحتال الصحيح (+2 نقط)</option>
                  <option value="no_votes">حد ما غادي يصوت علي فـ الجولة (+3 نقط)</option>
                </select>
              </div>
            </div>
          </div>

        </div>
      </div>

      <button id="next-player-btn" class="btn-secondary hidden" onclick="nextPlayer()" style="margin-top:15px;">دوز للاعب التالي ➡</button>
    </div>

    <!-- 3. مرحلة النقاش واللعب -->
    <div id="gameplay-step" class="hidden">
      <h2>🔥 بدأ النقاش!</h2>

      <div id="starter-player-box" class="starter-player-banner">
        <span style="font-size:13px; color:#64748b; font-weight:bold;">🎯 النوبة غادي تبدأ عشوائياً من عند:</span>
        <h3 id="starter-player-name" style="margin:6px 0 0 0; font-size:24px; color:var(--starter-dynamic-color);"></h3>
      </div>

      <div id="wildcard-box" class="wild-card hidden">
        <strong>🃏 كارت الجولة:</strong> <span id="wildcard-text"></span>
      </div>

      <div id="timer-box" class="hidden">
        <div id="timer-display" class="timer-display">03:00</div>
        <button class="btn-secondary" onclick="toggleTimerPause()" id="timer-btn">إيقاف / تشغيل ⏸️</button>
      </div>

      <button class="btn-primary" onclick="handleDiscussionEnd()">الانتقال لـ النتائج / التصويت ➡</button>
    </div>

    <!-- 4. مرحلة التصويت المتعدد -->
    <div id="voting-step" class="hidden">
      <h2 id="voter-turn-title" style="color:var(--player-dynamic-color);">دور التصويت</h2>
      <p style="font-size:14px; color:#64748b;">تقدر تختار أكثر من شخص شاك فيه فـ هاد الجولة:</p>
      
      <div id="voting-buttons-container"></div>

      <button class="btn-primary" onclick="confirmMultiVote()" style="margin-top:15px;">تأكيد التصويت 🗳</button>
    </div>

    <!-- 5. كشف النتائج المحدثة والجديدة -->
    <div id="result-step" class="hidden">
      <h2>📊 نتائج الجولة!</h2>
      
      <!-- كروت كشف الحقائق -->
      <div class="reveal-cards-grid">
        <div class="reveal-hero-card word-card">
          <div class="reveal-icon-circle">🔑</div>
          <div class="reveal-content-info">
            <div class="reveal-label">الكلمة السرية</div>
            <div class="reveal-value" id="revealed-word">---</div>
          </div>
        </div>

        <div class="reveal-hero-card impostor-card">
          <div class="reveal-icon-circle">🕵️</div>
          <div class="reveal-content-info">
            <div class="reveal-label">المحتال المطلوب</div>
            <div class="reveal-value" id="revealed-impostors">---</div>
          </div>
        </div>
      </div>

      <!-- ترتيب الأصوات والشكوك -->
      <div id="ranking-section-wrapper" class="results-ranking-box hidden">
        <div class="results-ranking-title">
          <span>🗳️ ترتيب الأصوات والشكوك:</span>
        </div>
        <div id="results-ranking-container"></div>
      </div>

      <!-- خيارات إضافة النقاط والتحكم -->
      <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 20px; padding: 14px; margin-top: 16px;">
        <span style="font-size: 13px; font-weight: bold; color: #64748b; display: block; margin-bottom: 8px;">إضافة نقاط الجولة للحساب التراكمي:</span>
        <div style="display:flex; gap:10px;">
          <button class="btn-secondary" style="margin-top:0;" onclick="addScoreToWinners('innocents')">ربح المواطنين (+1)</button>
          <button class="btn-danger" style="margin-top:0;" onclick="addScoreToWinners('impostors')">ربح المحتالين (+3)</button>
        </div>
      </div>

      <button class="btn-primary" onclick="resetGame()" style="margin-top:15px;">لعبة جديدة 🔄</button>
    </div>

  </div>

  <!-- التبويبات السفلية العائمة -->
  <nav id="bottom-tabs-bar" class="bottom-tabs">
    <button class="tab-btn active" onclick="switchTab('tab-categories', this)">
      <span>📂</span> التصنيفات
    </button>
    <button class="tab-btn" onclick="switchTab('tab-players', this)">
      <span>👥</span> اللاعبين
    </button>
    <button class="tab-btn" onclick="switchTab('tab-options', this)">
      <span>⚙️</span> الخيارات
    </button>
  </nav>

  <!-- Modal تعديل الكلمات -->
  <div id="words-modal" class="modal-overlay hidden">
    <div class="modal-content">
      <div style="display:flex; justify-space-between; align-items:center; border-bottom:1px solid #e2e8f0; padding-bottom:10px;">
        <h3 id="modal-cat-title" style="margin:0; color:#0f172a; font-size:16px;">تعديل كلمات التصنيف</h3>
        <span onclick="closeWordsModal()" style="cursor:pointer; font-weight:bold; font-size:20px; color:#64748b;">✕</span>
      </div>
      
      <div id="modal-words-list" class="words-tags-container"></div>
      
      <div style="display:flex; gap:8px; margin-top:auto;">
        <input type="text" id="add-single-word-input" placeholder="إضافة كلمة جديدة..." style="flex:1; padding:10px; border-radius:10px; border:1px solid #cbd5e1; font-size:14px;">
        <button class="btn-secondary" style="width:auto; margin:0; padding:10px 18px;" onclick="addWordToCurrentCategory()">إضافة</button>
      </div>
    </div>
  </div>

  <script>
    const defaultColors = ["#7c3aed", "#2563eb", "#059669", "#d97706", "#dc2626", "#db2777", "#0891b2", "#ea580c"];

    const defaultDatabase = {
      "🍲 مأكولات ومشروبات": [
        "حريرة", "كسكس", "طاجين", "رفيسة", "سفنج", "حرشة", "مسمن", "بغرير", "شواية", "كفتة", "بولفاف", 
        "بسطيلة", "معقودة", "شاورما", "تاكوس", "بيتزا", "بانيني", "فريت", "بيصرة", "بوبوش", "زريعة", "كاوكاو", 
        "مكسرات", "تمر", "شريحة (تين مجفف)", "فرماج", "زبدة", "سلو", "دانون", "رايبي", "أتاي", "قهوة", 
        "عصير أفوكادو", "عصير ليمون", "حليب", "لبن", "شوكلاط", "كيكة"
      ],
      "💻 تكنولوجيا وأجهزة": [
        "تلفون", "بيسي (PC)", "بلايستيشن (PlayStation)", "كاسك (سماعات)", "باف (مكبر صوت)", "شارجور", 
        "تيليكوماند", "تلفزة", "كاميرا", "راديو", "واتساب", "إنستغرام", "يوتيوب", "تيك توك", "روبوت", "ساعة ذكية"
      ],
      "👔 ملابس وإكسسوارات": [
        "جلابة", "كاندورة", "بيجامة", "سورڤيتنانت", "تريكو", "قميجة", "جاكيت", "كابوتش", "صباط", "سبرديلة", 
        "صندالة", "بليغة", "كاسكيطة", "بونيه", "خاتم", "دمليج (سوار)", "نظارات", "مكياج", "قفطان", "شربيل"
      ],
      "🏛️ أماكن ومرافق": [
        "قهوة", "مطعم", "حمام", "مرجان", "حانوت", "سويقة", "بحر", "مسبح", "حديقة", "غابة", "مطار", 
        "محطة", "سينما", "سبيطار", "فارماسي", "بانكة", "بوسطة", "ملعب", "لاصال (Gym)", "كورنيش", "حبوس"
      ],
      "🚘 وسائل نقل": [
        "طاكسي", "طوبيس", "ترامواي", "قطار", "طيارة", "موتور", "بيسيكليت", "باطو", "تريبورتور", "رموك"
      ],
      "💼 مهن وشخصيات": [
        "طبيب", "فرملي", "أستاذ", "بوليسي", "جدارمي", "عساس", "شفار", "محتال", "طباخ", "حلاق", 
        "عريس", "عروسة", "نكافة", "حكم", "مدرب"
      ],
      "🌿 طبيعة وحيوانات": [
        "مش", "كلب", "حنش", "عقرب", "حمامة", "شجرة", "نخلة", "جبل", "شتا", "تلج", "شمس", "قمر", "واد", "غيس (طين)"
      ],
      "🌐 دول وعواصم": [
        "اليابان", "فرنسا", "البرازيل", "مصر", "تركيا", "ألمانيا", "أمريكا", "إسبانيا", "إيطاليا", "باريس", 
        "طوكيو", "لندن", "كندا", "الصين", "السعودية", "الإمارات", "المغرب", "تونس", "الجزائر", "قطر"
      ]
    };

    const wildCardsList = [
      "🗣️ جولة الهمس: كولشي كيهضر غير بـ الهمس فقط!",
      "☝️ كلمة واحدة: كل لاعب عندو الحق يقول كلمة واحدة فقط فـ دورو!",
      "❓ نعم أم لا: الأسئلة والأجوبة خاصها تكون بـ نعم أو لا فقط!",
      "🎭 الممثل الجامت: استعمل الحركات والإشارات فقط بدون كلام لشرح كلمتك!",
      "⏱ سرعة السرعة: عندك 5 ثواني فقط للتحدث وإبداء رأيك!"
    ];

    let database = JSON.parse(localStorage.getItem("impostor_db_v14")) || defaultDatabase;
    let scores = JSON.parse(localStorage.getItem("impostor_scores_v14")) || {};
    let savedPlayers = JSON.parse(localStorage.getItem("impostor_saved_players_v14")) || [
      { name: "لاعب 1", color: "#7c3aed" },
      { name: "لاعب 2", color: "#2563eb" },
      { name: "لاعب 3", color: "#059669" },
      { name: "لاعب 4", color: "#d97706" }
    ];

    let playerCount = savedPlayers.length;
    let selectedImpostorMode = "1";

    let gameState = {
      step: "setup",
      players: [],
      playerRoles: [],
      playerBets: {},
      votes: {},
      currentWord: "",
      currentCategory: "",
      impostorNames: [],
      currentIndex: 0,
      votingIndex: 0,
      timerSeconds: 0,
      timerRunning: false,
      starterPlayer: null,
      wildCardText: ""
    };

    let timerInterval = null;
    let selectedCategoryForModal = "";
    let hasRevealedWord = false;
    let currentVoterSelectedTargets = [];

    // أنيميشن عند الضغط على الشاشة
    document.addEventListener('pointerdown', function(e) {
      const ripple = document.createElement('div');
      ripple.className = 'tap-ripple';
      const size = 50;
      ripple.style.width = ripple.style.height = `${size}px`;
      ripple.style.left = `${e.clientX - size / 2}px`;
      ripple.style.top = `${e.clientY - size / 2}px`;
      document.body.appendChild(ripple);
      setTimeout(() => ripple.remove(), 500);
    });

    function triggerVibrate(ms = 40) {
      if ("vibrate" in navigator) navigator.vibrate(ms);
    }

    function playSound(freq = 440, type = 'sine', duration = 0.1) {
      try {
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        const osc = audioCtx.createOscillator();
        const gain = audioCtx.createGain();
        osc.type = type;
        osc.frequency.value = freq;
        osc.connect(gain);
        gain.connect(audioCtx.destination);
        osc.start();
        gain.gain.exponentialRampToValueAtTime(0.00001, audioCtx.currentTime + duration);
        osc.stop(audioCtx.currentTime + duration);
      } catch (e) {}
    }

    window.onload = () => {
      renderCategories();
      generatePlayerInputs();
      renderScoreboard();
      loadSavedOptions();
      loadActiveGameState();
    };

    function saveOptionsToStorage() {
      const options = {
        detective: document.getElementById("role-detective").checked,
        joker: document.getElementById("role-joker").checked,
        seer: document.getElementById("role-seer").checked,
        wordHint: document.getElementById("opt-word-hint").checked,
        playerAsWord: document.getElementById("opt-player-as-word").checked,
        enableVoting: document.getElementById("opt-enable-voting").checked,
        betting: document.getElementById("opt-betting").checked,
        impostorFriends: document.getElementById("opt-impostor-friends").checked,
        wildcard: document.getElementById("opt-wildcard").checked,
        timer: document.getElementById("opt-timer").checked,
        timerMinutes: document.getElementById("timer-minutes").value,
        impostorMode: selectedImpostorMode
      };
      localStorage.setItem("impostor_options_v14", JSON.stringify(options));
    }

    function loadSavedOptions() {
      const saved = localStorage.getItem("impostor_options_v14");
      if (saved) {
        try {
          const opts = JSON.parse(saved);
          if (opts.detective !== undefined) document.getElementById("role-detective").checked = opts.detective;
          if (opts.joker !== undefined) document.getElementById("role-joker").checked = opts.joker;
          if (opts.seer !== undefined) document.getElementById("role-seer").checked = opts.seer;
          if (opts.wordHint !== undefined) document.getElementById("opt-word-hint").checked = opts.wordHint;
          if (opts.playerAsWord !== undefined) document.getElementById("opt-player-as-word").checked = opts.playerAsWord;
          if (opts.enableVoting !== undefined) document.getElementById("opt-enable-voting").checked = opts.enableVoting;
          if (opts.betting !== undefined) document.getElementById("opt-betting").checked = opts.betting;
          if (opts.impostorFriends !== undefined) document.getElementById("opt-impostor-friends").checked = opts.impostorFriends;
          if (opts.wildcard !== undefined) document.getElementById("opt-wildcard").checked = opts.wildcard;
          if (opts.timer !== undefined) {
            document.getElementById("opt-timer").checked = opts.timer;
            toggleTimerInput();
          }
          if (opts.timerMinutes) document.getElementById("timer-minutes").value = opts.timerMinutes;
          if (opts.impostorMode) setImpostorCount(opts.impostorMode, false);
        } catch (e) {
          console.error("Error loading options", e);
        }
      }
    }

    function toggleOption(id) {
      const checkbox = document.getElementById(id);
      checkbox.checked = !checkbox.checked;
      if (id === 'opt-timer') toggleTimerInput();
      saveOptionsToStorage();
    }

    function changePlayerCount(delta) {
      const newCount = playerCount + delta;
      if (newCount >= 3 && newCount <= 15) {
        playerCount = newCount;
        document.getElementById("players-count-display").innerText = playerCount;
        syncSavedPlayersList();
        generatePlayerInputs();
        triggerVibrate(20);
      }
    }

    function removePlayerAt(index) {
      if (playerCount <= 3) {
        alert("خاص يبقى على الأقل 3 ديال اللاعبين!");
        return;
      }
      syncSavedPlayersList();
      savedPlayers.splice(index, 1);
      playerCount = savedPlayers.length;
      document.getElementById("players-count-display").innerText = playerCount;
      generatePlayerInputs();
      savePlayersData();
      triggerVibrate(30);
    }

    function syncSavedPlayersList() {
      const rows = document.querySelectorAll("#players-inputs-list .player-row");
      if (rows.length > 0) {
        savedPlayers = Array.from(rows).map((row, i) => ({
          name: row.querySelector("input[type='text']").value.trim() || `لاعب ${i + 1}`,
          color: row.querySelector("input[type='color']").value
        }));
      }
      savePlayersData();
    }

    function setImpostorCount(mode, save = true) {
      selectedImpostorMode = mode;
      document.querySelectorAll('.impostor-pill').forEach(pill => pill.classList.remove('active'));
      const activePill = document.getElementById(`imp-pill-${mode}`);
      if (activePill) activePill.classList.add('active');
      if (save) saveOptionsToStorage();
      triggerVibrate(20);
    }

    function saveActiveGameState() {
      localStorage.setItem("impostor_active_game_v14", JSON.stringify(gameState));
    }

    function clearActiveGameState() {
      localStorage.removeItem("impostor_active_game_v14");
    }

    function loadActiveGameState() {
      const saved = localStorage.getItem("impostor_active_game_v14");
      if (saved) {
        try {
          gameState = JSON.parse(saved);
          if (gameState.step && gameState.step !== "setup") {
            restoreGameStepUI();
          }
        } catch (e) {
          console.error("Error loading saved game state", e);
        }
      }
    }

    function restoreGameStepUI() {
      hideAllSteps();
      document.getElementById("bottom-tabs-bar").classList.add("hidden");

      if (gameState.step === "role") {
        document.getElementById("role-step").classList.remove("hidden");
        updateTurnUI();
      } else if (gameState.step === "gameplay") {
        document.getElementById("gameplay-step").classList.remove("hidden");
        document.getElementById("starter-player-name").innerText = gameState.starterPlayer.name;
        document.documentElement.style.setProperty('--starter-dynamic-color', gameState.starterPlayer.color);

        if (gameState.wildCardText) {
          document.getElementById("wildcard-text").innerText = gameState.wildCardText;
          document.getElementById("wildcard-box").classList.remove("hidden");
        }

        if (gameState.timerSeconds > 0) {
          document.getElementById("timer-box").classList.remove("hidden");
          updateTimerDisplay();
          if (gameState.timerRunning) runTimer();
        }
      } else if (gameState.step === "voting") {
        document.getElementById("voting-step").classList.remove("hidden");
        updateVoterUI();
      } else if (gameState.step === "result") {
        document.getElementById("result-step").classList.remove("hidden");
        showFinalResultsUI();
      }
    }

    function hideAllSteps() {
      document.getElementById("setup-step").classList.add("hidden");
      document.getElementById("role-step").classList.add("hidden");
      document.getElementById("gameplay-step").classList.add("hidden");
      document.getElementById("voting-step").classList.add("hidden");
      document.getElementById("result-step").classList.add("hidden");
    }

    function switchTab(tabId, btnEl) {
      document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
      document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');
      btnEl.classList.add('active');
      playSound(400, 'sine', 0.05);
    }

    function saveDatabase() { localStorage.setItem("impostor_db_v14", JSON.stringify(database)); }
    function saveScores() { localStorage.setItem("impostor_scores_v14", JSON.stringify(scores)); renderScoreboard(); }
    function savePlayersData() { localStorage.setItem("impostor_saved_players_v14", JSON.stringify(savedPlayers)); }

    function renderCategories() {
      const container = document.getElementById("categories-container");
      container.innerHTML = "";
      Object.keys(database).forEach((cat, index) => {
        container.innerHTML += `
          <div class="category-card-item" onclick="toggleOption('cat-${index}')">
            <div class="category-info">
              <input type="checkbox" id="cat-${index}" value="${cat}" checked onclick="event.stopPropagation();">
              <label for="cat-${index}">${cat} (${database[cat].length})</label>
            </div>
            <button class="btn-view-icon" onclick="event.stopPropagation(); openWordsModal('${cat}')" title="عرض الكلمات">👁️</button>
          </div>
        `;
      });
    }

    function generatePlayerInputs() {
      const listContainer = document.getElementById("players-inputs-list");
      listContainer.innerHTML = "";

      for (let i = 0; i < playerCount; i++) {
        const pName = savedPlayers[i]?.name || `لاعب ${i + 1}`;
        const pColor = savedPlayers[i]?.color || defaultColors[i % defaultColors.length];
        listContainer.innerHTML += `
          <div class="player-row">
            <span class="player-number-badge">${i + 1}</span>
            <input type="color" value="${pColor}" onchange="syncSavedPlayersList()">
            <input type="text" value="${pName}" placeholder="اسم اللاعب ${i + 1}" onchange="syncSavedPlayersList()">
            <button class="btn-delete-player" onclick="removePlayerAt(${i})" title="حذف اللاعب">✕</button>
          </div>
        `;
      }
    }

    function renderScoreboard() {
      const tbody = document.getElementById("scoreboard-body");
      tbody.innerHTML = "";
      Object.keys(scores).forEach(name => {
        tbody.innerHTML += `<tr><td><b>${name}</b></td><td>${scores[name]} نقطة</td></tr>`;
      });
    }

    function toggleTimerInput() {
      const isChecked = document.getElementById("opt-timer").checked;
      document.getElementById("timer-input-box").classList.toggle("hidden", !isChecked);
    }

    function setDynamicThemeColor(color) {
      document.documentElement.style.setProperty('--player-dynamic-color', color);
      const card = document.getElementById("main-card");
      card.style.borderColor = color;
      card.style.boxShadow = `0 15px 35px rgba(0,0,0,0.05), 0 0 20px ${color}33`;
    }

    function startGame() {
      syncSavedPlayersList();
      triggerVibrate(60);
      playSound(520, 'sine', 0.2);

      const players = savedPlayers;

      if (players.length < 3) return alert("خاص يكون على الأقل 3 ديال اللاعبين!");

      const selectedCats = Array.from(document.querySelectorAll("#categories-container input:checked")).map(cb => cb.value);
      if (selectedCats.length === 0) return alert("اختار تصنيف واحد على الأقل!");

      let currentWord = "";
      let currentCategory = "";
      let wordPool = [];

      const allowPlayerNameAsWord = document.getElementById("opt-player-as-word").checked;
      
      if (allowPlayerNameAsWord && Math.random() < 0.25) {
        const randomPlayer = players[Math.floor(Math.random() * players.length)];
        currentWord = randomPlayer.name;
        currentCategory = "أسماء اللاعبين 👤";
        players.forEach(p => wordPool.push(p.name));
      } else {
        const chosenCat = selectedCats[Math.floor(Math.random() * selectedCats.length)];
        currentCategory = chosenCat;
        wordPool = database[chosenCat];
        currentWord = wordPool[Math.floor(Math.random() * wordPool.length)];
      }

      let numImpostors = selectedImpostorMode === "random" 
        ? Math.floor(Math.random() * Math.max(1, Math.floor(players.length / 2))) + 1 
        : parseInt(selectedImpostorMode);

      if (numImpostors >= players.length) return alert("عدد المحتالين خاصو يكون أقل من عدد اللاعبين!");

      let impIndices = [];
      while (impIndices.length < numImpostors) {
        let rand = Math.floor(Math.random() * players.length);
        if (!impIndices.includes(rand)) impIndices.push(rand);
      }

      const impostorNames = impIndices.map(idx => players[idx].name);
      const enableImpostorFriends = document.getElementById("opt-impostor-friends").checked;

      let availableForRoles = players.map((_, i) => i).filter(i => !impIndices.includes(i));
      let detectiveIdx = -1, jokerIdx = -1, seerIdx = -1;

      if (document.getElementById("role-detective").checked && availableForRoles.length > 0) {
        detectiveIdx = availableForRoles.splice(Math.floor(Math.random() * availableForRoles.length), 1)[0];
      }
      if (document.getElementById("role-joker").checked && availableForRoles.length > 0) {
        jokerIdx = availableForRoles.splice(Math.floor(Math.random() * availableForRoles.length), 1)[0];
      }
      if (document.getElementById("role-seer").checked && availableForRoles.length > 0) {
        seerIdx = availableForRoles.splice(Math.floor(Math.random() * availableForRoles.length), 1)[0];
      }

      const playerRoles = players.map((p, i) => {
        if (impIndices.includes(i)) {
          let otherImpostors = impostorNames.filter(n => n !== p.name);
          let friendsText = (enableImpostorFriends && otherImpostors.length > 0) ? `<br><small style="color:#fef08a;">🤝 صديقك فـ الاحتيال: ${otherImpostors.join(" ، ")}</small>` : "";
          return { role: "impostor", text: "🕵️ أنت هو المحتال!", desc: `حاول تخبي وما تخلي حد يفيق بيك!${friendsText}` };
        } else if (i === detectiveIdx) {
          let innocentNames = players.filter((_, idx) => !impIndices.includes(idx) && idx !== detectiveIdx);
          let knownInnocent = innocentNames[Math.floor(Math.random() * innocentNames.length)]?.name || "لا يوجد";
          return { role: "detective", text: `🔎 الكلمة هي: ${currentWord}`, desc: `معلومة خاصة: (${knownInnocent}) شخص بريء أكيد!` };
        } else if (i === jokerIdx) {
          let otherWords = wordPool.filter(w => w !== currentWord);
          let fakeWord = otherWords[Math.floor(Math.random() * otherWords.length)] || "كلمة مضللة";
          return { role: "joker", text: `🃏 الكلمة هي: ${fakeWord}`, desc: "ملاحظة: كلمتك قد تكون مضللة وقريبة للكلمة الأصلية!" };
        } else if (i === seerIdx) {
          let impText = impostorNames.join(" ، ");
          return { role: "seer", text: `🧙‍♂️ الكلمة هي: ${currentWord}`, desc: `⚡ قدرة السحر كشفات ليك المحتال مباشرة: <b style="color:#fca5a5;">${impText}</b>` };
        } else {
          return { role: "innocent", text: `🔑 الكلمة هي: ${currentWord}`, desc: "أنت مواطن بريء، اكتشف المحتال!" };
        }
      });

      gameState = {
        step: "role",
        players,
        playerRoles,
        playerBets: {},
        votes: {},
        currentWord,
        currentCategory,
        impostorNames,
        currentIndex: 0,
        votingIndex: 0,
        timerSeconds: document.getElementById("opt-timer").checked ? (parseInt(document.getElementById("timer-minutes").value) || 3) * 60 : 0,
        timerRunning: false,
        starterPlayer: null,
        wildCardText: ""
      };

      saveActiveGameState();

      hideAllSteps();
      document.getElementById("bottom-tabs-bar").classList.add("hidden");
      document.getElementById("role-step").classList.remove("hidden");
      
      const enableBetting = document.getElementById("opt-betting").checked;
      document.getElementById("bet-section").classList.toggle("hidden", !enableBetting);

      updateTurnUI();
    }

    function updateTurnUI() {
      const p = gameState.players[gameState.currentIndex];
      setDynamicThemeColor(p.color);
      hasRevealedWord = false;

      // إرجاع البطاقة لوجهها الأصلي
      document.getElementById("main-player-card").classList.remove("flipped");

      document.getElementById("card-player-name").innerText = p.name;
      document.getElementById("player-step-text").innerText = `لاعب ${gameState.currentIndex + 1} من ${gameState.players.length}`;
      
      const progressPercent = ((gameState.currentIndex + 1) / gameState.players.length) * 100;
      document.getElementById("progress-fill-bar").style.width = `${progressPercent}%`;

      document.getElementById("next-player-btn").classList.add("hidden");
    }

    function startHold(e) {
      if (e) e.preventDefault();
      triggerVibrate(30);
      playSound(350, 'triangle', 0.1);
      hasRevealedWord = true;

      const pData = gameState.playerRoles[gameState.currentIndex];
      const secretText = document.getElementById("secret-text");
      
      secretText.innerText = pData.text;
      
      document.getElementById("role-desc").innerHTML = pData.desc;

      const hintBadge = document.getElementById("secret-hint-badge");
      const isHintEnabled = document.getElementById("opt-word-hint").checked;
      if (isHintEnabled && pData.role !== 'impostor' && gameState.currentCategory) {
        hintBadge.innerText = `💡 تلميح: الكلمة من تصنيف (${gameState.currentCategory})`;
        hintBadge.classList.remove("hidden");
      } else {
        hintBadge.classList.add("hidden");
      }

      document.getElementById("main-player-card").classList.add("flipped");
    }

    function endHold(e) {
      if (e) e.preventDefault();
      if (hasRevealedWord) {
        document.getElementById("main-player-card").classList.remove("flipped");
        document.getElementById("next-player-btn").classList.remove("hidden");
      }
    }

    function nextPlayer() {
      triggerVibrate(20);
      playSound(750, 'sine', 0.1);

      if (document.getElementById("opt-betting").checked) {
        gameState.playerBets[gameState.players[gameState.currentIndex].name] = document.getElementById("player-bet-select").value;
      }

      gameState.currentIndex++;
      saveActiveGameState();

      if (gameState.currentIndex < gameState.players.length) {
        updateTurnUI();
      } else {
        startGameplayPhase();
      }
    }

    function startGameplayPhase() {
      gameState.step = "gameplay";
      gameState.starterPlayer = gameState.players[Math.floor(Math.random() * gameState.players.length)];

      if (document.getElementById("opt-wildcard").checked) {
        gameState.wildCardText = wildCardsList[Math.floor(Math.random() * wildCardsList.length)];
      }

      saveActiveGameState();

      hideAllSteps();
      document.getElementById("gameplay-step").classList.remove("hidden");

      document.getElementById("starter-player-name").innerText = gameState.starterPlayer.name;
      document.documentElement.style.setProperty('--starter-dynamic-color', gameState.starterPlayer.color);

      if (gameState.wildCardText) {
        document.getElementById("wildcard-text").innerText = gameState.wildCardText;
        document.getElementById("wildcard-box").classList.remove("hidden");
      } else {
        document.getElementById("wildcard-box").classList.add("hidden");
      }

      if (gameState.timerSeconds > 0) {
        document.getElementById("timer-box").classList.remove("hidden");
        gameState.timerRunning = true;
        runTimer();
      } else {
        document.getElementById("timer-box").classList.add("hidden");
      }
    }

    function runTimer() {
      clearInterval(timerInterval);
      updateTimerDisplay();
      timerInterval = setInterval(() => {
        gameState.timerSeconds--;
        saveActiveGameState();
        updateTimerDisplay();

        if (gameState.timerSeconds <= 0) {
          clearInterval(timerInterval);
          gameState.timerRunning = false;
          saveActiveGameState();
          triggerVibrate([200, 100, 200, 100, 400]);
          alert("⏰ تسالى وقت النقاش!");
        }
      }, 1000);
    }

    function updateTimerDisplay() {
      const m = Math.floor(gameState.timerSeconds / 60).toString().padStart(2, '0');
      const s = (gameState.timerSeconds % 60).toString().padStart(2, '0');
      document.getElementById("timer-display").innerText = `${m}:${s}`;
    }

    function toggleTimerPause() {
      if (timerInterval) { 
        clearInterval(timerInterval); 
        timerInterval = null; 
        gameState.timerRunning = false;
      } else if (gameState.timerSeconds > 0) { 
        gameState.timerRunning = true;
        runTimer(); 
      }
      saveActiveGameState();
    }

    function handleDiscussionEnd() {
      clearInterval(timerInterval);
      gameState.timerRunning = false;

      if (document.getElementById("opt-enable-voting").checked) {
        gameState.step = "voting";
        gameState.votingIndex = 0;
        saveActiveGameState();

        hideAllSteps();
        document.getElementById("voting-step").classList.remove("hidden");
        updateVoterUI();
      } else {
        showFinalResults();
      }
    }

    function updateVoterUI() {
      const voter = gameState.players[gameState.votingIndex];
      setDynamicThemeColor(voter.color);
      currentVoterSelectedTargets = [];

      document.getElementById("voter-turn-title").innerText = `دور التصويت: ${voter.name}`;
      const container = document.getElementById("voting-buttons-container");
      container.innerHTML = "";

      gameState.players.forEach(target => {
        if (target.name !== voter.name) {
          const div = document.createElement("div");
          div.className = "multi-vote-card";
          div.id = `vote-card-${target.name}`;
          div.innerHTML = `
            <span>صوت على: <b>${target.name}</b></span>
            <div class="checkbox-icon">✓</div>
          `;
          div.onclick = () => toggleSelectTarget(target.name, div);
          container.appendChild(div);
        }
      });
    }

    function toggleSelectTarget(targetName, el) {
      triggerVibrate(20);
      playSound(600, 'sine', 0.05);

      if (currentVoterSelectedTargets.includes(targetName)) {
        currentVoterSelectedTargets = currentVoterSelectedTargets.filter(t => t !== targetName);
        el.classList.remove("selected");
      } else {
        currentVoterSelectedTargets.push(targetName);
        el.classList.add("selected");
      }
    }

    function confirmMultiVote() {
      const voterName = gameState.players[gameState.votingIndex].name;
      gameState.votes[voterName] = [...currentVoterSelectedTargets];

      triggerVibrate(30);
      playSound(750, 'sine', 0.1);

      gameState.votingIndex++;
      saveActiveGameState();

      if (gameState.votingIndex < gameState.players.length) {
        updateVoterUI();
      } else {
        showFinalResults();
      }
    }

    function showFinalResults() {
      gameState.step = "result";
      saveActiveGameState();

      hideAllSteps();
      document.getElementById("result-step").classList.remove("hidden");
      showFinalResultsUI();
    }

    function showFinalResultsUI() {
      document.getElementById("revealed-word").innerText = gameState.currentWord;
      document.getElementById("revealed-impostors").innerText = gameState.impostorNames.join(" ، ");

      const container = document.getElementById("results-ranking-container");
      const wrapper = document.getElementById("ranking-section-wrapper");
      container.innerHTML = "";

      if (document.getElementById("opt-enable-voting").checked && Object.keys(gameState.votes).length > 0) {
        wrapper.classList.remove("hidden");
        let voteCounts = {};
        gameState.players.forEach(p => voteCounts[p.name] = 0);

        let totalVotesCast = 0;
        Object.values(gameState.votes).forEach(targetList => {
          if (Array.isArray(targetList)) {
            targetList.forEach(target => {
              voteCounts[target] = (voteCounts[target] || 0) + 1;
              totalVotesCast++;
            });
          }
        });

        let sorted = gameState.players.map(p => ({ 
          name: p.name, 
          color: p.color, 
          count: voteCounts[p.name] || 0 
        })).sort((a, b) => b.count - a.count);

        const maxVotes = sorted[0]?.count || 1;

        sorted.forEach((item, index) => {
          const isTopVoted = index === 0 && item.count > 0;
          const percentage = totalVotesCast > 0 ? Math.round((item.count / totalVotesCast) * 100) : 0;
          
          container.innerHTML += `
            <div class="result-rank-card ${isTopVoted ? 'top-voted' : ''}">
              <div class="rank-card-header">
                <span class="rank-player-name" style="color:${item.color}">
                  <span style="width:10px; height:10px; border-radius:50%; background:${item.color}; display:inline-block;"></span>
                  ${item.name}
                  ${isTopVoted ? '<span class="top-voted-badge">🚨 الأكثر شكوكاً</span>' : ''}
                </span>
                <span class="rank-votes-count">${item.count} أصوات</span>
              </div>
              <div class="vote-bar-track">
                <div class="vote-bar-fill" style="width: ${percentage}%"></div>
              </div>
            </div>
          `;
        });

        if (document.getElementById("opt-betting").checked) {
          gameState.players.forEach(p => {
            if (!scores[p.name]) scores[p.name] = 0;
            const bet = gameState.playerBets[p.name];
            const pVotes = gameState.votes[p.name] || [];
            
            const guessedImpostor = pVotes.some(v => gameState.impostorNames.includes(v));
            if (bet === 'find_impostor' && guessedImpostor) scores[p.name] += 2;
            else if (bet === 'no_votes' && (voteCounts[p.name] || 0) === 0) scores[p.name] += 3;
          });
          saveScores();
        }
      } else {
        wrapper.classList.add("hidden");
      }
    }

    function addScoreToWinners(type) {
      gameState.players.forEach(p => {
        if (!scores[p.name]) scores[p.name] = 0;
        if (type === 'innocents' && !gameState.impostorNames.includes(p.name)) scores[p.name] += 1;
        else if (type === 'impostors' && gameState.impostorNames.includes(p.name)) scores[p.name] += 3;
      });
      saveScores();
      alert("تم تحديث النقاط بنجاح! 🏆");
    }

    function resetGame() {
      clearInterval(timerInterval);
      clearActiveGameState();
      gameState.step = "setup";

      hideAllSteps();
      document.getElementById("setup-step").classList.remove("hidden");
      document.getElementById("bottom-tabs-bar").classList.remove("hidden");
      setDynamicThemeColor("#7c3aed");
    }

    function openWordsModal(catName) {
      selectedCategoryForModal = catName;
      document.getElementById("modal-cat-title").innerText = `كلمات تصنيف: ${catName}`;
      renderModalWords();
      document.getElementById("words-modal").classList.remove("hidden");
    }

    function renderModalWords() {
      const list = database[selectedCategoryForModal] || [];
      const container = document.getElementById("modal-words-list");
      container.innerHTML = "";
      list.forEach((word, idx) => {
        container.innerHTML += `<div class="word-tag">${word} <span onclick="removeWordFromCategory(${idx})">✕</span></div>`;
      });
    }

    function addWordToCurrentCategory() {
      const input = document.getElementById("add-single-word-input");
      const word = input.value.trim();
      if (word && selectedCategoryForModal) {
        database[selectedCategoryForModal].push(word);
        saveDatabase();
        renderModalWords();
        renderCategories();
        input.value = "";
      }
    }

    function removeWordFromCategory(idx) {
      if (selectedCategoryForModal && database[selectedCategoryForModal]) {
        database[selectedCategoryForModal].splice(idx, 1);
        saveDatabase();
        renderModalWords();
        renderCategories();
      }
    }

    function closeWordsModal() { document.getElementById("words-modal").classList.add("hidden"); }

    function addCustomCategory() {
      const catName = document.getElementById("new-cat-name").value.trim();
      const catWords = document.getElementById("new-cat-words").value.trim();
      if (!catName || !catWords) return alert("المرجو كتابة الاسم والكلمات!");
      database[catName] = catWords.split(",").map(w => w.trim()).filter(w => w.length > 0);
      saveDatabase();
      renderCategories();
      document.getElementById("new-cat-name").value = "";
      document.getElementById("new-cat-words").value = "";
    }
  </script>
</body>
</html>
