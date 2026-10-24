<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>7-sinf Geografiya: 3.6. Yer yuzi aholisi — Telegram Online Test</title>
<!-- Telegram Mini App (WebApp) rasmiy SDK -->
<script src="https://telegram.org/js/telegram-web-app.js"></script>
<style>
  :root {
    --bg-deep: #060b16;
    --bg-card: rgba(15, 23, 42, 0.84);
    --primary: #0ea5e9;
    --primary-light: #38bdf8;
    --accent: #6366f1;
    --gold: #f59e0b;
    --gold-light: #fde047;
    --success: #10b981;
    --danger: #ef4444;
    --text-main: #f8fafc;
    --text-muted: #94a3b8;
    --border-glass: rgba(255, 255, 255, 0.12);
    --tg-blue: #24A1DE;
  }

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    user-select: none;
    -webkit-user-select: none;
    -webkit-tap-highlight-color: transparent;
  }

  body {
    font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
    background: var(--bg-deep);
    color: var(--text-main);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    overflow-x: hidden;
    position: relative;
  }

  .ambient-bg {
    position: fixed;
    inset: 0;
    z-index: 0;
    overflow: hidden;
    pointer-events: none;
  }

  .orb {
    position: absolute;
    border-radius: 50%;
    filter: blur(90px);
    opacity: 0.32;
    animation: floatOrb 14s infinite alternate ease-in-out;
  }

  .orb-1 { width: 380px; height: 380px; background: #0ea5e9; top: -90px; left: -90px; }
  .orb-2 { width: 420px; height: 420px; background: #6366f1; bottom: -100px; right: -90px; animation-delay: -5s; }
  .orb-3 { width: 280px; height: 280px; background: #10b981; top: 40%; left: 50%; opacity: 0.18; animation-delay: -9s; }

  @keyframes floatOrb {
    0% { transform: translate(0, 0) scale(1); }
    100% { transform: translate(35px, -30px) scale(1.08); }
  }

  /* Yuqori Navigatsiya Paneli */
  .top-bar {
    position: sticky;
    top: 0;
    z-index: 50;
    background: rgba(15, 23, 42, 0.92);
    backdrop-filter: blur(16px);
    border-bottom: 1px solid var(--border-glass);
    padding: 10px 18px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    box-shadow: 0 4px 25px rgba(0, 0, 0, 0.45);
  }

  .brand {
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .brand-badge {
    background: linear-gradient(135deg, #24A1DE, #0ea5e9);
    color: #fff;
    font-weight: 900;
    font-size: 11.5px;
    padding: 5px 10px;
    border-radius: 8px;
    letter-spacing: 0.4px;
    display: flex;
    align-items: center;
    gap: 5px;
    box-shadow: 0 0 14px rgba(36, 161, 222, 0.45);
  }

  .brand-title {
    font-size: 15px;
    font-weight: 800;
    color: #f8fafc;
  }

  .brand-sub {
    font-size: 11.5px;
    color: var(--text-muted);
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .live-dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #10b981;
    box-shadow: 0 0 8px #10b981;
    display: inline-block;
    animation: pulseLive 1.5s infinite;
  }

  @keyframes pulseLive {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.45; transform: scale(1.25); }
  }

  .top-actions {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 8px;
  }

  .btn {
    background: rgba(255, 255, 255, 0.07);
    color: #f8fafc;
    border: 1px solid var(--border-glass);
    padding: 7px 13px;
    border-radius: 10px;
    font-size: 12.5px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s ease;
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }

  .btn:hover {
    background: rgba(255, 255, 255, 0.14);
    transform: translateY(-1px);
  }

  .btn-primary {
    background: linear-gradient(135deg, #0ea5e9, #6366f1);
    border-color: transparent;
    box-shadow: 0 4px 15px rgba(14, 165, 233, 0.35);
  }

  .btn-tg {
    background: linear-gradient(135deg, #24A1DE, #1d86b8);
    border-color: transparent;
    color: #fff;
    box-shadow: 0 4px 15px rgba(36, 161, 222, 0.4);
  }

  .btn-gold {
    background: linear-gradient(135deg, rgba(245, 158, 11, 0.25), rgba(217, 119, 6, 0.35));
    border-color: rgba(245, 158, 11, 0.55);
    color: #fde047;
    box-shadow: 0 0 14px rgba(245, 158, 11, 0.2);
  }

  .history-count-badge {
    background: #f59e0b;
    color: #0f172a;
    font-weight: 900;
    font-size: 11px;
    padding: 1px 6px;
    border-radius: 99px;
  }

  /* Asosiy Konteyner */
  .main-wrap {
    position: relative;
    z-index: 10;
    flex: 1;
    max-width: 960px;
    width: 100%;
    margin: 16px auto;
    padding: 0 14px 24px;
    display: flex;
    flex-direction: column;
    gap: 14px;
  }

  /* O'quvchi profili va Jonli Statistika */
  .status-card {
    background: var(--bg-card);
    backdrop-filter: blur(16px);
    border: 1px solid var(--border-glass);
    border-radius: 18px;
    padding: 14px 18px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 14px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.35);
  }

  .user-box {
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .user-avatar {
    width: 44px;
    height: 44px;
    border-radius: 13px;
    background: linear-gradient(135deg, #24A1DE, #6366f1);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    font-weight: 900;
    color: #fff;
    box-shadow: 0 4px 15px rgba(36, 161, 222, 0.4);
  }

  .user-info label {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 10.5px;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 3px;
    font-weight: 700;
  }

  .tg-verified {
    background: rgba(36, 161, 222, 0.2);
    color: #38bdf8;
    border: 1px solid rgba(36, 161, 222, 0.4);
    padding: 1px 6px;
    border-radius: 4px;
    font-size: 9.5px;
  }

  .student-input {
    background: rgba(255, 255, 255, 0.06);
    border: 1px dashed rgba(255, 255, 255, 0.28);
    color: #fff;
    font-size: 15px;
    font-weight: 800;
    padding: 5px 10px;
    border-radius: 8px;
    width: 230px;
    outline: none;
    user-select: text;
    -webkit-user-select: text;
  }

  .student-input:focus {
    border-color: var(--gold-light);
    background: rgba(255, 255, 255, 0.12);
  }

  .stats-row {
    display: flex;
    align-items: center;
    gap: 8px;
    flex-wrap: wrap;
  }

  .stat-item {
    background: rgba(9, 13, 22, 0.65);
    border: 1px solid rgba(255, 255, 255, 0.08);
    padding: 6px 12px;
    border-radius: 11px;
    text-align: center;
    min-width: 72px;
  }

  .stat-item .val {
    font-size: 16px;
    font-weight: 900;
    display: block;
    font-variant-numeric: tabular-nums;
  }

  .stat-item .lbl {
    font-size: 9.5px;
    color: var(--text-muted);
    text-transform: uppercase;
    font-weight: 700;
  }

  .c-green { color: #34d399; }
  .c-red { color: #f87171; }
  .c-blue { color: #38bdf8; }
  .c-gold { color: #fbbf24; }

  /* 20 ta savol trekeri (Dots) */
  .tracker-card {
    background: var(--bg-card);
    backdrop-filter: blur(16px);
    border: 1px solid var(--border-glass);
    border-radius: 16px;
    padding: 12px 16px;
  }

  .tracker-header {
    display: flex;
    justify-content: space-between;
    font-size: 12px;
    font-weight: 700;
    color: var(--text-muted);
    margin-bottom: 8px;
  }

  .dots-grid {
    display: grid;
    grid-template-columns: repeat(20, 1fr);
    gap: 5px;
  }

  .step-dot {
    height: 26px;
    border-radius: 6px;
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid rgba(255, 255, 255, 0.1);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 10.5px;
    font-weight: 800;
    color: var(--text-muted);
    transition: all 0.25s ease;
  }

  .step-dot.current {
    background: rgba(14, 165, 233, 0.25);
    border-color: #38bdf8;
    color: #fff;
    box-shadow: 0 0 10px rgba(56, 189, 248, 0.45);
    transform: scale(1.06);
  }

  .step-dot.done-ok {
    background: rgba(16, 185, 129, 0.28);
    border-color: #10b981;
    color: #6ee7b7;
  }

  .step-dot.done-bad {
    background: rgba(239, 68, 68, 0.28);
    border-color: #ef4444;
    color: #fca5a5;
  }

  /* Savol va Variantlar Maydoni */
  .quiz-card {
    background: var(--bg-card);
    backdrop-filter: blur(20px);
    border: 1px solid var(--border-glass);
    border-radius: 22px;
    padding: 22px 24px;
    position: relative;
    overflow: hidden;
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.45);
    transition: border-color 0.3s, box-shadow 0.3s;
  }

  .quiz-card.flash-ok {
    border-color: var(--success);
    box-shadow: 0 0 35px rgba(16, 185, 129, 0.3);
  }

  .quiz-card.flash-bad {
    border-color: var(--danger);
    box-shadow: 0 0 35px rgba(239, 68, 68, 0.3);
  }

  .q-meta {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 12px;
  }

  .q-num-pill {
    background: linear-gradient(135deg, rgba(14, 165, 233, 0.25), rgba(99, 102, 241, 0.25));
    border: 1px solid rgba(56, 189, 248, 0.4);
    color: #7dd3fc;
    font-size: 12px;
    font-weight: 800;
    padding: 4px 12px;
    border-radius: 99px;
  }

  .q-topic-pill {
    background: rgba(245, 158, 11, 0.14);
    border: 1px solid rgba(245, 158, 11, 0.35);
    color: #fde047;
    font-size: 11.5px;
    font-weight: 700;
    padding: 4px 10px;
    border-radius: 8px;
  }

  .q-title {
    font-size: 19.5px;
    font-weight: 800;
    line-height: 1.42;
    color: #ffffff;
    margin-bottom: 20px;
  }

  .options-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .opt-btn {
    background: rgba(30, 41, 59, 0.78);
    border: 2px solid rgba(255, 255, 255, 0.1);
    border-radius: 15px;
    padding: 14px 16px;
    color: #f1f5f9;
    font-size: 15px;
    font-weight: 600;
    text-align: left;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 12px;
    transition: all 0.18s ease;
    position: relative;
  }

  .opt-btn:hover:not(:disabled) {
    border-color: var(--primary-light);
    background: rgba(14, 165, 233, 0.14);
    transform: translateY(-1px);
  }

  .opt-btn:active:not(:disabled) {
    transform: scale(0.98);
  }

  .opt-letter {
    width: 35px;
    height: 35px;
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.08);
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 900;
    font-size: 14px;
    color: #cbd5e1;
    flex-shrink: 0;
  }

  .opt-text {
    flex: 1;
    line-height: 1.32;
  }

  .opt-icon {
    font-size: 19px;
    font-weight: 900;
    opacity: 0;
    transform: scale(0.4);
    transition: all 0.25s ease;
  }

  .opt-btn.is-correct {
    background: rgba(16, 185, 129, 0.24) !important;
    border-color: #10b981 !important;
    box-shadow: 0 0 22px rgba(16, 185, 129, 0.35);
    color: #ecfdf5;
  }

  .opt-btn.is-correct .opt-letter { background: #10b981 !important; color: #fff !important; }
  .opt-btn.is-correct .opt-icon { opacity: 1; transform: scale(1); color: #34d399; }

  .opt-btn.is-wrong {
    background: rgba(239, 68, 68, 0.24) !important;
    border-color: #ef4444 !important;
    box-shadow: 0 0 22px rgba(239, 68, 68, 0.35);
    color: #fef2f2;
    animation: shake 0.42s ease;
  }

  .opt-btn.is-wrong .opt-letter { background: #ef4444 !important; color: #fff !important; }
  .opt-btn.is-wrong .opt-icon { opacity: 1; transform: scale(1); color: #f87171; }

  @keyframes shake {
    0%, 100% { transform: translateX(0); }
    25% { transform: translateX(-6px); }
    50% { transform: translateX(6px); }
    75% { transform: translateX(-4px); }
  }

  .feedback-banner {
    margin-top: 15px;
    padding: 11px 16px;
    border-radius: 12px;
    font-size: 14px;
    font-weight: 700;
    display: none;
    align-items: center;
    justify-content: space-between;
  }

  .feedback-banner.show { display: flex; }
  .feedback-banner.ok { background: rgba(16, 185, 129, 0.18); border: 1px solid rgba(16, 185, 129, 0.45); color: #6ee7b7; }
  .feedback-banner.bad { background: rgba(239, 68, 68, 0.18); border: 1px solid rgba(239, 68, 68, 0.45); color: #fca5a5; }

  /* Modallar */
  .modal-backdrop {
    position: fixed;
    inset: 0;
    background: rgba(6, 11, 22, 0.9);
    backdrop-filter: blur(12px);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 200;
    padding: 14px;
    overflow-y: auto;
  }

  .modal-backdrop.active { display: flex; }

  .result-modal {
    background: linear-gradient(180deg, #1e293b 0%, #0f172a 100%);
    border: 2px solid rgba(245, 158, 11, 0.4);
    border-radius: 22px;
    max-width: 920px;
    width: 100%;
    max-height: 94vh;
    overflow-y: auto;
    padding: 20px 24px;
    text-align: center;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.85);
  }

  .result-title {
    font-size: 25px;
    font-weight: 900;
    background: linear-gradient(90deg, #fde047, #f59e0b, #fbbf24);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 4px;
  }

  .result-sub {
    font-size: 13.5px;
    color: #cbd5e1;
    margin-bottom: 14px;
  }

  .result-grid {
    display: grid;
    grid-template-columns: 1.3fr 1fr;
    gap: 16px;
    align-items: center;
  }

  .cert-box {
    background: rgba(9, 13, 22, 0.75);
    border: 2px solid rgba(245, 158, 11, 0.35);
    border-radius: 14px;
    padding: 8px;
  }

  #certCanvas {
    width: 100%;
    height: auto;
    border-radius: 8px;
    display: block;
  }

  .cert-edit-row {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    margin-top: 8px;
  }

  .cert-edit-row input {
    background: #0f172a;
    border: 1px solid rgba(245, 158, 11, 0.5);
    color: #fde047;
    padding: 5px 10px;
    border-radius: 8px;
    font-size: 13.5px;
    font-weight: 700;
    outline: none;
    width: 200px;
    text-align: center;
    user-select: text;
    -webkit-user-select: text;
  }

  .summary-panel {
    background: rgba(30, 41, 59, 0.72);
    border: 1px solid var(--border-glass);
    border-radius: 16px;
    padding: 15px;
    text-align: left;
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .sum-row {
    display: flex;
    justify-content: space-between;
    font-size: 13.5px;
    padding: 5px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.07);
  }

  .btn-download {
    background: linear-gradient(135deg, #f59e0b, #d97706);
    color: #0f172a;
    font-weight: 900;
    font-size: 14px;
    padding: 11px 16px;
    border-radius: 11px;
    border: none;
    cursor: pointer;
    width: 100%;
    box-shadow: 0 6px 20px rgba(245, 158, 11, 0.35);
  }

  .btn-share-tg {
    background: linear-gradient(135deg, #24A1DE, #0284c7);
    color: #fff;
    font-weight: 800;
    font-size: 14px;
    padding: 11px 16px;
    border-radius: 11px;
    border: none;
    cursor: pointer;
    width: 100%;
    box-shadow: 0 6px 20px rgba(36, 161, 222, 0.35);
  }

  /* =========================================================
     ONLAYN REYTING VA CLOUD ROOM SOZLAMALARI MODALI
     ========================================================= */
  .history-modal-card {
    background: #0f172a;
    border: 2px solid rgba(36, 161, 222, 0.45);
    border-radius: 20px;
    max-width: 1080px;
    width: 100%;
    max-height: 92vh;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    box-shadow: 0 25px 70px rgba(0, 0, 0, 0.9);
  }

  .qa-header {
    padding: 14px 20px;
    background: #1e293b;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid var(--border-glass);
  }

  .cloud-bar {
    background: rgba(36, 161, 222, 0.12);
    border-bottom: 1px solid rgba(36, 161, 222, 0.3);
    padding: 10px 20px;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
    font-size: 12.5px;
  }

  .cloud-status {
    display: flex;
    align-items: center;
    gap: 8px;
    font-weight: 700;
    color: #7dd3fc;
  }

  .history-summary-bar {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 12px 20px;
    background: rgba(30, 41, 59, 0.7);
    border-bottom: 1px solid rgba(255, 255, 255, 0.08);
  }

  .sum-card {
    background: rgba(15, 23, 42, 0.85);
    border: 1px solid rgba(255, 255, 255, 0.08);
    border-radius: 11px;
    padding: 9px 12px;
    display: flex;
    flex-direction: column;
    gap: 2px;
  }

  .sum-card .s-lbl { font-size: 10.5px; color: var(--text-muted); text-transform: uppercase; font-weight: 700; }
  .sum-card .s-val { font-size: 18px; font-weight: 900; color: #f8fafc; }

  .history-controls-bar {
    padding: 10px 20px;
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    align-items: center;
    justify-content: space-between;
    background: rgba(15, 23, 42, 0.95);
    border-bottom: 1px solid rgba(255, 255, 255, 0.08);
  }

  .search-input, .sort-select {
    background: #1e293b;
    border: 1px solid rgba(255, 255, 255, 0.18);
    color: #fff;
    padding: 7px 11px;
    border-radius: 8px;
    font-size: 12.5px;
    outline: none;
    user-select: text;
    -webkit-user-select: text;
  }

  .history-table-wrap {
    padding: 0 20px 18px;
    overflow-y: auto;
    flex: 1;
  }

  .history-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
    font-size: 13px;
  }

  .history-table th {
    background: #1e293b;
    color: #cbd5e1;
    font-weight: 800;
    text-align: left;
    padding: 10px;
    position: sticky;
    top: 0;
    z-index: 5;
    border-bottom: 2px solid rgba(255, 255, 255, 0.1);
    font-size: 11.5px;
    text-transform: uppercase;
  }

  .history-table td {
    padding: 10px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    color: #f1f5f9;
    vertical-align: middle;
  }

  .rank-medal {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 26px;
    height: 26px;
    border-radius: 50%;
    font-weight: 900;
    font-size: 12px;
  }
  .rank-1 { background: #fde047; color: #0f172a; box-shadow: 0 0 10px #fde047; }
  .rank-2 { background: #e2e8f0; color: #0f172a; }
  .rank-3 { background: #d97706; color: #fff; }

  .pct-badge {
    display: inline-block;
    padding: 3px 9px;
    border-radius: 99px;
    font-weight: 800;
    font-size: 12px;
  }

  .pct-high { background: rgba(16, 185, 129, 0.2); color: #34d399; border: 1px solid rgba(16, 185, 129, 0.45); }
  .pct-mid { background: rgba(245, 158, 11, 0.2); color: #fbbf24; border: 1px solid rgba(245, 158, 11, 0.45); }
  .pct-low { background: rgba(239, 68, 68, 0.2); color: #f87171; border: 1px solid rgba(239, 68, 68, 0.45); }

  .grade-pill {
    display: inline-block;
    padding: 3px 8px;
    border-radius: 6px;
    font-size: 11px;
    font-weight: 800;
  }
  .grade-5 { background: rgba(16, 185, 129, 0.2); color: #6ee7b7; border: 1px solid rgba(16, 185, 129, 0.4); }
  .grade-4 { background: rgba(56, 189, 248, 0.2); color: #7dd3fc; border: 1px solid rgba(56, 189, 248, 0.4); }
  .grade-3 { background: rgba(245, 158, 11, 0.2); color: #fde047; border: 1px solid rgba(245, 158, 11, 0.4); }
  .grade-2 { background: rgba(239, 68, 68, 0.2); color: #fca5a5; border: 1px solid rgba(239, 68, 68, 0.4); }

  .qa-card {
    background: #0f172a;
    border: 1px solid var(--border-glass);
    border-radius: 20px;
    max-width: 960px;
    width: 100%;
    max-height: 88vh;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }

  .qa-body {
    padding: 18px 20px;
    overflow-y: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .qa-item {
    background: rgba(30, 41, 59, 0.72);
    border: 1px solid rgba(255, 255, 255, 0.08);
    border-radius: 12px;
    padding: 12px;
  }

  .qa-item-q { font-size: 13px; font-weight: 700; color: #f8fafc; margin-bottom: 7px; }
  .qa-item-opts { list-style: none; font-size: 12px; display: flex; flex-direction: column; gap: 4px; }
  .qa-item-opts li { padding: 4px 8px; border-radius: 6px; background: rgba(255, 255, 255, 0.03); color: #cbd5e1; }
  .qa-item-opts li.correct-ans { background: rgba(16, 185, 129, 0.22); border: 1px solid rgba(16, 185, 129, 0.5); color: #6ee7b7; font-weight: 700; }

  .cloud-config-box {
    background: #090d16;
    border-bottom: 1px solid rgba(255,255,255,0.1);
    padding: 12px 20px;
    display: none;
    flex-direction: column;
    gap: 8px;
    font-size: 12px;
  }
  .cloud-config-box.show { display: flex; }

  @media (max-width: 768px) {
    .options-grid { grid-template-columns: 1fr; }
    .dots-grid { grid-template-columns: repeat(10, 1fr); }
    .result-grid { grid-template-columns: 1fr; }
    .qa-body { grid-template-columns: 1fr; }
    .q-title { font-size: 17px; }
    .history-summary-bar { grid-template-columns: repeat(2, 1fr); }
    .student-input { width: 185px; }
  }
</style>
</head>
<body>

<div class="ambient-bg">
  <div class="orb orb-1"></div>
  <div class="orb orb-2"></div>
  <div class="orb orb-3"></div>
</div>

<!-- YUQORI PANEL -->
<header class="top-bar">
  <div class="brand">
    <span class="brand-badge">✈️ TELEGRAM MINI APP</span>
    <div>
      <span class="brand-title">7-sinf Geografiya: 3.6. Yer yuzi aholisi</span>
      <span class="brand-sub">
        <span class="live-dot"></span>
        <span id="onlineStatusLabel">Onlayn Reyting Faol (Hammaga ko'rinadi)</span>
      </span>
    </div>
  </div>

  <div class="top-actions">
    <button class="btn btn-gold" onclick="openLeaderboardModal()">
      🌐 Onlayn Reyting <span class="history-count-badge" id="savedCountBadge">0</span>
    </button>
    <button class="btn" onclick="openQAModal()">📖 Javoblar</button>
    <button class="btn" onclick="toggleSound()" id="soundBtn">🔊</button>
    <button class="btn btn-primary" onclick="startQuiz()">🔄 Yangi Test</button>
  </div>
</header>

<!-- ASOSIY MAYDON -->
<main class="main-wrap">

  <!-- O'quvchi profili va Ko'rsatkichlar -->
  <section class="status-card">
    <div class="user-box">
      <div class="user-avatar" id="userAvatar">🎓</div>
      <div class="user-info">
        <label for="studentName">
          <span>Ishtirokchi:</span>
          <span class="tg-verified" id="tgBadge">Telegram O'yinchisi</span>
        </label>
        <input type="text" id="studentName" class="student-input" value="Ishtirokchi" maxlength="30" onchange="saveLocalSettings()">
      </div>
    </div>

    <div class="stats-row">
      <div class="stat-item">
        <span class="val c-green" id="statCorrect">0</span>
        <span class="lbl">To'g'ri</span>
      </div>
      <div class="stat-item">
        <span class="val c-red" id="statWrong">0</span>
        <span class="lbl">Xato</span>
      </div>
      <div class="stat-item">
        <span class="val c-blue" id="statAcc">100%</span>
        <span class="lbl">Foiz</span>
      </div>
      <div class="stat-item">
        <span class="val c-gold" id="statStreak">0 🔥</span>
        <span class="lbl">Seriya</span>
      </div>
      <div class="stat-item">
        <span class="val" id="statTimer">00:00</span>
        <span class="lbl">Vaqt</span>
      </div>
    </div>
  </section>

  <!-- 20 ta savol jarayon indikatori -->
  <section class="tracker-card">
    <div class="tracker-header">
      <span id="progressText">Savol: 1 / 20</span>
      <span>🌐 Yechilgan natija avtomatik ravishda umumiy Telegram reytingga tushadi</span>
    </div>
    <div class="dots-grid" id="dotsContainer"></div>
  </section>

  <!-- Savol Karta Maydoni -->
  <section class="quiz-card" id="quizCard">
    <div class="q-meta">
      <span class="q-num-pill" id="qNumberBadge">1-SAVOL</span>
      <span class="q-topic-pill" id="qTopicBadge">Yer yuzi aholisi</span>
    </div>

    <div class="q-title" id="qText">Savol yuklanmoqda...</div>

    <div class="options-grid" id="optionsContainer"></div>

    <div class="feedback-banner" id="feedbackBanner"></div>
  </section>

</main>

<!-- NATIJA VA PNG SERTIFIKAT MODALI -->
<div class="modal-backdrop" id="resultModal">
  <div class="result-modal">
    <div class="result-title">🏆 TEST MUVAFFAQIYATLI YAKUNLANDI!</div>
    <div class="result-sub" id="resSubText"></div>

    <div class="result-grid">
      <div class="cert-box">
        <canvas id="certCanvas" width="1200" height="840"></canvas>
        <div class="cert-edit-row">
          <span style="font-size:12px; color:#cbd5e1;">Sertifikatdagi ism:</span>
          <input type="text" id="certNameInput" oninput="updateCertName()">
        </div>
      </div>

      <div class="summary-panel">
        <h3 style="color:#38bdf8; font-size:17px;">📊 Sizning ko'rsatkichingiz</h3>
        <div class="sum-row"><span>Ishtirokchi:</span><strong id="sumName" style="color:#fff;">-</strong></div>
        <div class="sum-row"><span>To'g'ri javoblar:</span><strong id="sumCorrect" class="c-green">0 ta</strong></div>
        <div class="sum-row"><span>Xato javoblar:</span><strong id="sumWrong" class="c-red">0 ta</strong></div>
        <div class="sum-row"><span>O'zlashtirish foizi:</span><strong id="sumAcc" class="c-blue">0%</strong></div>
        <div class="sum-row"><span>Sarflangan vaqt:</span><strong id="sumTime" class="c-gold">0.0 s</strong></div>
        <div class="sum-row"><span>Baho:</span><strong id="sumGrade" style="color:#fde047;">-</strong></div>

        <div id="syncNoticeBox" style="background: rgba(16, 185, 129, 0.15); border: 1px solid rgba(16, 185, 129, 0.4); color: #6ee7b7; padding: 7px 10px; border-radius: 9px; font-size: 11.5px; font-weight: 700; text-align: center;">
          ✅ Natijangiz Onlayn Reytingga saqlandi va hammaga ko'rinmoqda!
        </div>

        <button class="btn-share-tg" onclick="shareResultToTelegram()">
          ✈️ Natijani Telegram guruhga ulashish
        </button>

        <button class="btn-download" onclick="downloadCertificatePNG()">
          📥 Sertifikatni PNG formatda yuklab olish
        </button>

        <div style="display:flex; gap:8px; margin-top:4px;">
          <button class="btn btn-gold" style="flex:1; justify-content:center;" onclick="openLeaderboardModal()">🌐 Umumiy Reyting</button>
          <button class="btn btn-primary" style="flex:1; justify-content:center;" onclick="startQuiz()">🔄 Qayta ishlash</button>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- =========================================================
     UMUMIY ONLAYN REYTING (BARCHA FOYDALANUVCHILAR NATIJASI)
     ========================================================= -->
<div class="modal-backdrop" id="leaderboardModal">
  <div class="history-modal-card">
    <div class="qa-header">
      <div>
        <h3 style="font-size:17.5px; color:#fde047;">🌐 Barcha ishtirokchilarning Jonli Onlayn Reytingi</h3>
        <p style="font-size:11.5px; color:#94a3b8;">Telegram orqali kirib test yechgan barcha o'quvchilarning foizi va to'g'ri javoblari shu yerda hammaga ko'rinadi</p>
      </div>
      <button class="btn" onclick="closeLeaderboardModal()">✖ Yopish</button>
    </div>

    <!-- Onlayn Sinxronizatsiya Holati Paneli -->
    <div class="cloud-bar">
      <div class="cloud-status">
        <span class="live-dot"></span>
        <span id="cloudRoomStatusText">Umumiy Xona: Faol (Avto-sinxronizatsiya har 5 soniyada)</span>
      </div>
      <div style="display:flex; gap:8px; align-items:center;">
        <button class="btn" style="padding:5px 10px; font-size:11.5px;" onclick="syncFromCloudNow()">🔄 Hozir yangilash</button>
        <button class="btn" style="padding:5px 10px; font-size:11.5px;" onclick="toggleCloudConfig()">⚙️ Bulut (Server) sozlamasi</button>
      </div>
    </div>

    <!-- O'qituvchi uchun ixtiyoriy maxsus bulut / Firebase ulash oynasi -->
    <div class="cloud-config-box" id="cloudConfigBox">
      <div style="color:#fde047; font-weight:700;">
        💡 O'yin standart holatda umumiy bulut xotiraga (JSONBlob Cloud / LocalSync) avtomatik ulangan. Agar o'zingizning shaxsiy Firebase Realtime Database bazangizni ulamoqchi bo'lsangiz, URL manzilini kiriting:
      </div>
      <div style="display:flex; gap:8px; flex-wrap:wrap;">
        <input type="text" id="customCloudUrlInput" class="search-input" style="flex:1;" placeholder="Masalan: https://sizning-baza.firebaseio.com/natijalar.json">
        <button class="btn btn-primary" onclick="saveCustomCloudUrl()">💾 Saqlash va Ulash</button>
        <button class="btn btn-tg" onclick="createNewSharedCloudRoom()">⚡ 1-Klikda Yangi Umumiy Bulut Xona yaratish</button>
      </div>
      <div id="cloudShareLinkInfo" style="color:#6ee7b7; font-size:11.5px;"></div>
    </div>

    <!-- Umumiy statistika kartochkalari -->
    <div class="history-summary-bar">
      <div class="sum-card">
        <span class="s-lbl">Jami o'quvchilar</span>
        <span class="s-val" id="sumTotalPlayers" style="color:#38bdf8;">0 ta</span>
      </div>
      <div class="sum-card">
        <span class="s-lbl">O'rtacha Foiz</span>
        <span class="s-val" id="sumAvgPercent" style="color:#fde047;">0%</span>
      </div>
      <div class="sum-card">
        <span class="s-lbl">Peshqadam (1-o'rin)</span>
        <span class="s-val" id="sumBestScore" style="color:#34d399; font-size:15px;">-</span>
      </div>
      <div class="sum-card">
        <span class="s-lbl">A'lochilar (5 baho)</span>
        <span class="s-val" id="sumExcellentCount" style="color:#a78bfa;">0 ta</span>
      </div>
    </div>

    <!-- Qidiruv va Boshqaruv -->
    <div class="history-controls-bar">
      <div style="display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
        <input type="text" id="historySearchInput" class="search-input" placeholder="🔍 Ism yoki @username qidirish..." oninput="renderLeaderboardTable()">
        <select id="historySortSelect" class="sort-select" onchange="renderLeaderboardTable()">
          <option value="leaderboard">🏆 Reyting bo'yicha (Eng yuqori % va tez)</option>
          <option value="newest">🕒 Eng oxirgi yechganlar birinchi</option>
          <option value="correct_desc">✅ To'g'ri javobi ko'plar birinchi</option>
        </select>
      </div>

      <div style="display:flex; gap:8px; flex-wrap:wrap;">
        <button class="btn btn-primary" onclick="saveCurrentAttemptManually()">
          ➕ Joriy natijani hozir saqlash
        </button>
        <button class="btn" onclick="exportHistoryCSV()" style="color:#7dd3fc;">
          📥 Excel (CSV) yuklab olish
        </button>
        <button class="btn" onclick="clearAllHistory()" style="color:#f87171;">
          🗑️ Tozalash
        </button>
      </div>
    </div>

    <!-- Jadval -->
    <div class="history-table-wrap">
      <table class="history-table">
        <thead>
          <tr>
            <th style="width:55px;">O'rin</th>
            <th>Ishtirokchi (Telegram)</th>
            <th>To'g'ri javob</th>
            <th>Xato</th>
            <th>Test Foizi (20 tadan)</th>
            <th>Aniqlik</th>
            <th>Vaqt</th>
            <th>Baho</th>
            <th>Sana va vaqt</th>
          </tr>
        </thead>
        <tbody id="historyTableBody"></tbody>
      </table>
      <div id="emptyHistoryMsg" class="empty-history" style="display:none; text-align:center; padding:35px; color:#94a3b8;">
        📭 Hozircha reytingda natijalar yo'q. Birinchi bo'lib testni yeching va 1-o'ringa chiqing!
      </div>
    </div>
  </div>
</div>

<!-- 20 TA SAVOL VA JAVOBLAR KALITI MODALI -->
<div class="modal-backdrop" id="qaModal">
  <div class="qa-card">
    <div class="qa-header">
      <div>
        <h3 style="font-size:16.5px; color:#f8fafc;">📚 7-sinf Geografiya: «3.6. Yer yuzi aholisi» — 20 ta test kaliti</h3>
      </div>
      <button class="btn" onclick="closeQAModal()">✖ Yopish</button>
    </div>
    <div class="qa-body" id="qaListContainer"></div>
  </div>
</div>

<script>
  /* =========================================================
     1. TELEGRAM MINI APP (WEBAPP) AVTOMATIK INTEGRATSIYASI
     ========================================================= */
  const tg = window.Telegram && window.Telegram.WebApp ? window.Telegram.WebApp : null;
  let telegramUser = {
    id: null,
    fullName: "",
    username: ""
  };

  function initTelegramMiniApp() {
    if (!tg) return;
    try {
      tg.ready();
      tg.expand(); // O'yinni Telegram ichida to'liq ekranga yoyish

      const user = tg.initDataUnsafe && tg.initDataUnsafe.user ? tg.initDataUnsafe.user : null;
      if (user) {
        telegramUser.id = user.id;
        const first = user.first_name || "";
        const last = user.last_name || "";
        telegramUser.fullName = (first + " " + last).trim();
        telegramUser.username = user.username ? "@" + user.username : "";

        const displayStr = telegramUser.username
          ? `${telegramUser.fullName} (${telegramUser.username})`
          : telegramUser.fullName;

        if (displayStr) {
          document.getElementById("studentName").value = displayStr;
          document.getElementById("tgBadge").textContent = "✔ Telegram Tasdiqlangan";
          document.getElementById("userAvatar").textContent = first ? first[0].toUpperCase() : "✈️";
        }
      }
    } catch (e) {}
  }

  function triggerHaptic(type) {
    if (!tg || !tg.HapticFeedback) return;
    try {
      if (type === "success") tg.HapticFeedback.notificationOccurred("success");
      else if (type === "error") tg.HapticFeedback.notificationOccurred("error");
      else tg.HapticFeedback.impactOccurred("light");
    } catch (e) {}
  }

  /* =========================================================
     2. 20 TA SAVOL BAZASI (7-SINF GEOGRAFIYA 3.6-MAVZU)
     ========================================================= */
  const MASTER_QUESTIONS = [
    {
      id: 1,
      topic: "Insoniyat vatani",
      q: "Ko'pchilik olimlar insoniyatning qadimgi vatani deb qaysi hududlarni hisoblaydilar?",
      options: [
        "Afrika va Janubi-g'arbiy Osiyo",
        "Janubiy Yevropa va Shimoliy Amerika",
        "Avstraliya va Sharqiy Osiyo",
        "Markaziy Amerika va Janubiy Osiyo"
      ],
      answer: "Afrika va Janubi-g'arbiy Osiyo"
    },
    {
      id: 2,
      topic: "Aholi tarqalishi",
      q: "Qadimgi odamlar o'z vatanidan qaysi materikdan boshqa barcha materiklarga asta-sekin tarqalgan?",
      options: ["Antarktidadan", "Avstraliyadan", "Janubiy Amerikadan", "Shimoliy Amerikadan"],
      answer: "Antarktidadan"
    },
    {
      id: 3,
      topic: "4-jadval: Aholi o'sishi",
      q: "4-jadval ma'lumotlariga ko'ra, Yer yuzi aholisi qaysi yilda 1 mlrd kishiga yetgan?",
      options: ["1804-yilda", "1927-yilda", "1750-yilda", "1900-yilda"],
      answer: "1804-yilda"
    },
    {
      id: 4,
      topic: "4-jadval: Aholi o'sishi",
      q: "Yer yuzi aholisi 1 mlrd kishidan 2 mlrd kishiga (1927-yilda) yetishi uchun necha yil vaqt ketgan?",
      options: ["123 yil", "33 yil", "100 yil", "54 yil"],
      answer: "123 yil"
    },
    {
      id: 5,
      topic: "4-jadval: Aholi o'sishi",
      q: "1960-yilda Yer yuzi aholisi 3 mlrd kishiga yetgan bo'lib, aholi soni 1 mlrd ga ko'payishi uchun necha yil ketgan?",
      options: ["33 yil", "14 yil", "123 yil", "25 yil"],
      answer: "33 yil"
    },
    {
      id: 6,
      topic: "4-jadval: Aholi o'sishi",
      q: "4-jadvalga ko'ra, 1974-yilda dunyo aholisi necha milliardga yetgan va buning uchun qancha vaqt sarflangan?",
      options: ["4 mlrd kishi (14 yil)", "5 mlrd kishi (13 yil)", "3 mlrd kishi (33 yil)", "6 mlrd kishi (12 yil)"],
      answer: "4 mlrd kishi (14 yil)"
    },
    {
      id: 7,
      topic: "4-jadval: Aholi o'sishi",
      q: "Yer yuzi aholisi qaysi yilda 5 mlrd kishiga yetgan (ko'payish uchun 13 yil vaqt ketgan)?",
      options: ["1987-yilda", "1974-yilda", "1999-yilda", "2011-yilda"],
      answer: "1987-yilda"
    },
    {
      id: 8,
      topic: "4-jadval: Aholi o'sishi",
      q: "Dunyo aholisi 6 mlrd (1999-yil) va 7 mlrd (2011-yil) kishiga yetishi uchun har bir milliardga necha yildan vaqt ketgan?",
      options: ["12 yildan", "14 yildan", "10 yildan", "15 yildan"],
      answer: "12 yildan"
    },
    {
      id: 9,
      topic: "BMT statistikasi",
      q: "BMT ma'lumotlariga ko'ra, 2020-yil 1-iyul holatida Yer yuzi aholisi qanchadan ortdi?",
      options: ["7 mlrd 773 mln kishidan", "7 mlrd 100 mln kishidan", "8 mlrd 500 mln kishidan", "6 mlrd 950 mln kishidan"],
      answer: "7 mlrd 773 mln kishidan"
    },
    {
      id: 10,
      topic: "Yirik davlatlar",
      q: "Darslikda keltirilgan aholi soni eng ko'p (100 mln dan ortiq) mamlakatlar qatorini toping.",
      options: [
        "Xitoy, Hindiston, AQSH, Indoneziya, Pokiston, Braziliya",
        "Xitoy, Kanada, Avstraliya, Qozog'iston, Ispaniya",
        "Hindiston, Germaniya, Fransiya, Italiya, Buyuk Britaniya",
        "Rossiya, Ukraina, Polsha, Turkiya, Argentina"
      ],
      answer: "Xitoy, Hindiston, AQSH, Indoneziya, Pokiston, Braziliya"
    },
    {
      id: 11,
      topic: "Yirik davlatlar (Afrikada)",
      q: "Afrika materigidan qaysi ikki davlat aholi soni 100 mln kishidan ortiq mamlakatlar ro'yxatiga kiritilgan?",
      options: ["Nigeriya va Efiopiya", "Misr va JAR", "Jazoir va Marokash", "Keniya va Sudan"],
      answer: "Nigeriya va Efiopiya"
    },
    {
      id: 12,
      topic: "Demografik portlash",
      q: "Qachon «demografik portlash», ya'ni Yer yuzi aholisining juda tez sur'atlar bilan o'sishi kuzatildi?",
      options: ["XX asrning 60-yillarida", "XIX asrning 50-yillarida", "XVIII asrning oxirida", "XXI asrning 20-yillarida"],
      answer: "XX asrning 60-yillarida"
    },
    {
      id: 13,
      topic: "Mintaqaviy tafovutlar",
      q: "Aholining o'sishi Afrika, Osiyo va Amerika mamlakatlarida yuqori bo'lsa, qaysi qit'aning ko'plab mamlakatlarida past ko'rsatkichga ega?",
      options: ["Yevropa", "Avstraliya", "Janubiy Amerika", "Shimoliy Amerika"],
      answer: "Yevropa"
    },
    {
      id: 14,
      topic: "Irqlar (39-rasm)",
      q: "Dunyo aholisi asosan nechta katta irqqa mansub va ular qaysilar?",
      options: [
        "4 ta: yevropeoid, mongoloid, negroid va avstraloid",
        "3 ta: yevropeoid, mongoloid va negroid",
        "5 ta: yevropeoid, osiyoid, afrikoid, amerikoid, avstraloid",
        "2 ta: g'arbiy va sharqiy irqlar"
      ],
      answer: "4 ta: yevropeoid, mongoloid, negroid va avstraloid"
    },
    {
      id: 15,
      topic: "Irqiy belgilar",
      q: "Inson zotida irqiy belgilarning (tana va soch rangi, ko'z, burun, lab tuzilishi) paydo bo'lishiga avvalo nima ta'sir etgan?",
      options: ["Tabiiy va iqlimiy sharoit", "Sanoat va transport rivojlanishi", "Davlat chegaralarining o'zgarishi", "Dengiz oqimlari va shamollar"],
      answer: "Tabiiy va iqlimiy sharoit"
    },
    {
      id: 16,
      topic: "Aholi joylashuvi",
      q: "Nima sababdan dunyo aholisining asosiy qismi dengiz va okean sohillariga yaqin masofada yashaydi?",
      options: [
        "Tabiiy sharoit qulayligi, arzon dengiz transportiga yaqinligi va yirik port-shaharlar borligi",
        "Sohillarda vulqon va zilzilalar umuman sodir bo'lmasligi",
        "Okean sohillarida o'rmonlar va daryolar yo'qligi",
        "Qurg'oqchil cho'l iqlimi hukmron bo'lgani uchun"
      ],
      answer: "Tabiiy sharoit qulayligi, arzon dengiz transportiga yaqinligi va yirik port-shaharlar borligi"
    },
    {
      id: 17,
      topic: "Insonning tabiatga ta'siri",
      q: "Inson xo'jalik faoliyatining qaysi sohasi geotizimlarni ayniqsa kuchli o'zgartirib, tabiiy o'simliklar maydonini qisqartiradi?",
      options: [
        "Qishloq xo'jaligi (yerlarni haydash, ekin ekish, chorvachilik)",
        "Baland tog' turizmi va alpinizm",
        "Ob-havoni sun'iy yo'ldoshdan kuzatish",
        "Dengiz transportida yuk tashish"
      ],
      answer: "Qishloq xo'jaligi (yerlarni haydash, ekin ekish, chorvachilik)"
    },
    {
      id: 18,
      topic: "Ekologik muammo",
      q: "Qurg'oqchil o'lkalarda ekin maydonlarini ortiqcha sug'orish qanday salbiy oqibatga olib keladi?",
      options: ["Tuproqning sho'r bosishiga", "O'rmonlarning tez ko'payishiga", "Vulqonlarning uyg'onishiga", "Havo haroratining keskin sovib ketishiga"],
      answer: "Tuproqning sho'r bosishiga"
    },
    {
      id: 19,
      topic: "Sanoat va ifloslanish",
      q: "Sanoat korxonalaridan chiqayotgan chiqindilar tabiat komponentlariga qanday taqsimlanib tushadi?",
      options: [
        "Gazsimon moddalar atmosferaga, qattiq va suyuq moddalar tuproq va suvga",
        "Barcha qattiq moddalar atmosferaga, gazlar esa faqat tuproqqa",
        "Faqatgina tog' jinslari va muzliklar tarkibiga",
        "Suyuq moddalar atmosferaga, gazsimon moddalar yer ostiga"
      ],
      answer: "Gazsimon moddalar atmosferaga, qattiq va suyuq moddalar tuproq va suvga"
    },
    {
      id: 20,
      topic: "Xarita tahlili (35-bet)",
      q: "35-betdagi aholi joylashuvi xaritasida to'q sariq va qizil ranglar bilan qanday hududlar tasvirlangan?",
      options: [
        "To'q sariq — aholi zich yashaydigan, qizil — aholi eng zich yashaydigan hududlar",
        "To'q sariq — o'rmonlar, qizil — baland tog' tizmalari",
        "To'q sariq — cho'llar, qizil — muzliklar bilan qoplangan hududlar",
        "To'q sariq — aholi yashamaydigan, qizil — kam o'zlashtirilgan hududlar"
      ],
      answer: "To'q sariq — aholi zich yashaydigan, qizil — aholi eng zich yashaydigan hududlar"
    }
  ];

  /* =========================================================
     3. ONLAYN BULUTLI XOTIRA (REAL-TIME SHARED LEADERBOARD)
     ========================================================= */
  const STORAGE_KEY_LOCAL_BOARD = "tg_geo7_3_6_shared_leaderboard_v2";
  const STORAGE_KEY_CLOUD_URL = "tg_geo7_3_6_cloud_endpoint_v2";
  const STORAGE_KEY_SETTINGS = "tg_geo7_3_6_user_settings_v2";

  // URL parametrida ?room=... bo'lsa avtomatik o'sha bulut xonasiga ulanadi
  const urlParams = new URLSearchParams(window.location.search);
  let cloudEndpointUrl = urlParams.get("room") || localStorage.getItem(STORAGE_KEY_CLOUD_URL) || "";

  // Agar hali umumiy bulut xonasi bo'lmasa, avtomatik ravishda bepul JSONBlob Cloud xonasini yaratib ulaymiz
  async function ensureCloudRoomInitialized() {
    if (cloudEndpointUrl) {
      document.getElementById("customCloudUrlInput").value = cloudEndpointUrl;
      await syncFromCloudNow();
      return;
    }
    try {
      const res = await fetch("https://jsonblob.com/api/jsonBlob", {
        method: "POST",
        headers: { "Content-Type": "application/json", "Accept": "application/json" },
        body: JSON.stringify({ results: getLocalLeaderboard() })
      });
      const loc = res.headers.get("Location") || res.headers.get("location");
      if (loc) {
        cloudEndpointUrl = loc.startsWith("http") ? loc : `https://jsonblob.com${loc}`;
        localStorage.setItem(STORAGE_KEY_CLOUD_URL, cloudEndpointUrl);
        document.getElementById("customCloudUrlInput").value = cloudEndpointUrl;
      }
    } catch (e) {}
  }

  function getLocalLeaderboard() {
    try {
      const raw = localStorage.getItem(STORAGE_KEY_LOCAL_BOARD);
      return raw ? JSON.parse(raw) : [];
    } catch (e) {
      return [];
    }
  }

  function saveLocalLeaderboard(list) {
    try {
      localStorage.setItem(STORAGE_KEY_LOCAL_BOARD, JSON.stringify(list));
      document.getElementById("savedCountBadge").textContent = list.length;
    } catch (e) {}
  }

  function mergeLeaderboards(localList, remoteList) {
    const map = new Map();
    [...localList, ...remoteList].forEach(item => {
      if (item && item.id) {
        map.set(item.id, item);
      }
    });
    return Array.from(map.values()).sort((a, b) => (b.timestamp || 0) - (a.timestamp || 0));
  }

  async function syncFromCloudNow() {
    const localList = getLocalLeaderboard();
    document.getElementById("savedCountBadge").textContent = localList.length;

    if (!cloudEndpointUrl) return;
    try {
      const res = await fetch(cloudEndpointUrl, { cache: "no-store" });
      if (!res.ok) return;
      const data = await res.json();

      let remoteList = [];
      if (Array.isArray(data)) {
        remoteList = data;
      } else if (data && Array.isArray(data.results)) {
        remoteList = data.results;
      } else if (data && typeof data === "object") {
        remoteList = Object.values(data);
      }

      const merged = mergeLeaderboards(localList, remoteList);
      saveLocalLeaderboard(merged);
      if (document.getElementById("leaderboardModal").classList.contains("active")) {
        renderLeaderboardTable();
      }
    } catch (e) {}
  }

  async function pushResultToCloud(newEntry) {
    const currentList = getLocalLeaderboard();
    const existingIdx = currentList.findIndex(i => i.id === newEntry.id);
    if (existingIdx >= 0) currentList[existingIdx] = newEntry;
    else currentList.unshift(newEntry);

    saveLocalLeaderboard(currentList);

    if (!cloudEndpointUrl) return;
    try {
      // Firebase yoki JSONBlob ekanligini tekshirib yozish
      if (cloudEndpointUrl.includes("firebaseio.com") || cloudEndpointUrl.includes("firebasedatabase.app")) {
        await fetch(cloudEndpointUrl, {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify(newEntry)
        });
      } else {
        // Avval bulutdagini olib, birlashtirib qayta yozamiz (barcha foydalanuvchilar bir vaqtda kirganda yo'qolmasligi uchun)
        let remoteList = [];
        try {
          const getRes = await fetch(cloudEndpointUrl, { cache: "no-store" });
          if (getRes.ok) {
            const d = await getRes.json();
            remoteList = Array.isArray(d) ? d : (d && Array.isArray(d.results) ? d.results : []);
          }
        } catch (err) {}

        const merged = mergeLeaderboards(currentList, remoteList);
        saveLocalLeaderboard(merged);

        await fetch(cloudEndpointUrl, {
          method: "PUT",
          headers: { "Content-Type": "application/json", "Accept": "application/json" },
          body: JSON.stringify({ results: merged })
        });
      }
    } catch (e) {}
  }

  async function createNewSharedCloudRoom() {
    try {
      const res = await fetch("https://jsonblob.com/api/jsonBlob", {
        method: "POST",
        headers: { "Content-Type": "application/json", "Accept": "application/json" },
        body: JSON.stringify({ results: getLocalLeaderboard() })
      });
      const loc = res.headers.get("Location") || res.headers.get("location");
      if (loc) {
        cloudEndpointUrl = loc.startsWith("http") ? loc : `https://jsonblob.com${loc}`;
        localStorage.setItem(STORAGE_KEY_CLOUD_URL, cloudEndpointUrl);
        document.getElementById("customCloudUrlInput").value = cloudEndpointUrl;

        const shareableGameUrl = `${window.location.origin}${window.location.pathname}?room=${encodeURIComponent(cloudEndpointUrl)}`;
        document.getElementById("cloudShareLinkInfo").innerHTML =
          `✅ Yangi umumiy xona yaratildi! O'quvchilarga ushbu havolani yuboring: <br><strong>${shareableGameUrl}</strong>`;
      }
    } catch (e) {
      alert("Bulut xona yaratishda internet aloqasini tekshiring.");
    }
  }

  function saveCustomCloudUrl() {
    const val = document.getElementById("customCloudUrlInput").value.trim();
    cloudEndpointUrl = val;
    localStorage.setItem(STORAGE_KEY_CLOUD_URL, val);
    syncFromCloudNow();
    alert("Bulut manzili saqlandi va sinxronizatsiya qilindi!");
  }

  function toggleCloudConfig() {
    document.getElementById("cloudConfigBox").classList.toggle("show");
  }

  /* =========================================================
     4. OVOZ EFEKTLARI VA SOZLAMALAR
     ========================================================= */
  let soundEnabled = true;
  let audioCtx = null;

  function playTone(type) {
    if (!soundEnabled) return;
    try {
      if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
      const now = audioCtx.currentTime;
      if (type === "correct") {
        const osc = audioCtx.createOscillator();
        const gain = audioCtx.createGain();
        osc.connect(gain);
        gain.connect(audioCtx.destination);
        osc.type = "sine";
        osc.frequency.setValueAtTime(523.25, now);
        osc.frequency.exponentialRampToValueAtTime(783.99, now + 0.15);
        gain.gain.setValueAtTime(0.18, now);
        gain.gain.exponentialRampToValueAtTime(0.001, now + 0.25);
        osc.start(now);
        osc.stop(now + 0.25);
      } else if (type === "wrong") {
        const osc = audioCtx.createOscillator();
        const gain = audioCtx.createGain();
        osc.connect(gain);
        gain.connect(audioCtx.destination);
        osc.type = "sawtooth";
        osc.frequency.setValueAtTime(210, now);
        osc.frequency.linearRampToValueAtTime(125, now + 0.22);
        gain.gain.setValueAtTime(0.15, now);
        gain.gain.exponentialRampToValueAtTime(0.001, now + 0.26);
        osc.start(now);
        osc.stop(now + 0.26);
      } else if (type === "finish") {
        [523.25, 659.25, 783.99, 1046.5].forEach((freq, idx) => {
          const o = audioCtx.createOscillator();
          const g = audioCtx.createGain();
          o.connect(g);
          g.connect(audioCtx.destination);
          o.type = "triangle";
          o.frequency.setValueAtTime(freq, now + idx * 0.1);
          g.gain.setValueAtTime(0.2, now + idx * 0.1);
          g.gain.exponentialRampToValueAtTime(0.001, now + idx * 0.1 + 0.35);
          o.start(now + idx * 0.1);
          o.stop(now + idx * 0.1 + 0.35);
        });
      }
    } catch (e) {}
  }

  function toggleSound() {
    soundEnabled = !soundEnabled;
    document.getElementById("soundBtn").textContent = soundEnabled ? "🔊" : "🔇";
    saveLocalSettings();
  }

  function loadLocalSettings() {
    try {
      const raw = localStorage.getItem(STORAGE_KEY_SETTINGS);
      if (!raw) return;
      const cfg = JSON.parse(raw);
      if (typeof cfg.soundEnabled === "boolean") {
        soundEnabled = cfg.soundEnabled;
        document.getElementById("soundBtn").textContent = soundEnabled ? "🔊" : "🔇";
      }
      if (cfg.studentName && !telegramUser.fullName) {
        document.getElementById("studentName").value = cfg.studentName;
      }
    } catch (e) {}
  }

  function saveLocalSettings() {
    try {
      localStorage.setItem(STORAGE_KEY_SETTINGS, JSON.stringify({
        soundEnabled,
        studentName: document.getElementById("studentName").value.trim() || "Ishtirokchi"
      }));
    } catch (e) {}
  }

  /* =========================================================
     5. ASOSIY TEST LOGIKASI VA AVTOMATIK REYTINGGA YOZISH
     ========================================================= */
  function shuffleArray(arr) {
    const copy = [...arr];
    for (let i = copy.length - 1; i > 0; i--) {
      const j = Math.floor(Math.random() * (i + 1));
      [copy[i], copy[j]] = [copy[j], copy[i]];
    }
    return copy;
  }

  let questions = [];
  let currentIndex = 0;
  let correctCount = 0;
  let wrongCount = 0;
  let streak = 0;
  let locked = false;
  let startTime = 0;
  let elapsedSec = 0;
  let timerInterval = null;
  let currentAttemptSaved = false;
  let lastSavedRecordId = null;

  function getGradeText(score) {
    if (score >= 18) return "A'LO (5 BAHO)";
    if (score >= 14) return "YAXSHI (4 BAHO)";
    if (score >= 10) return "QONIQARLI (3 BAHO)";
    return "KO'PROQ O'QISH KERAK";
  }

  function initDots() {
    const container = document.getElementById("dotsContainer");
    container.innerHTML = "";
    for (let i = 0; i < 20; i++) {
      const dot = document.createElement("div");
      dot.className = "step-dot" + (i === 0 ? " current" : "");
      dot.id = `dot-${i}`;
      dot.textContent = i + 1;
      container.appendChild(dot);
    }
  }

  function startQuiz() {
    if (!currentAttemptSaved && (correctCount + wrongCount) > 0) {
      autoSaveParticipantResult();
    }

    document.getElementById("resultModal").classList.remove("active");
    questions = shuffleArray(MASTER_QUESTIONS).map(q => ({
      ...q,
      shuffledOptions: shuffleArray(q.options)
    }));
    currentIndex = 0;
    correctCount = 0;
    wrongCount = 0;
    streak = 0;
    locked = false;
    elapsedSec = 0;
    currentAttemptSaved = false;
    lastSavedRecordId = null;
    startTime = performance.now();

    initDots();
    updateStatsUI();
    renderCurrentQuestion();

    if (timerInterval) clearInterval(timerInterval);
    timerInterval = setInterval(() => {
      elapsedSec = (performance.now() - startTime) / 1000;
      const m = String(Math.floor(elapsedSec / 60)).padStart(2, "0");
      const s = String(Math.floor(elapsedSec % 60)).padStart(2, "0");
      document.getElementById("statTimer").textContent = `${m}:${s}`;
    }, 100);
  }

  function renderCurrentQuestion() {
    const banner = document.getElementById("feedbackBanner");
    banner.className = "feedback-banner";

    if (currentIndex >= questions.length) {
      finishQuiz();
      return;
    }

    const qObj = questions[currentIndex];
    const qNum = currentIndex + 1;

    document.getElementById("progressText").textContent = `Savol: ${qNum} / 20`;
    document.getElementById("qNumberBadge").textContent = `${qNum}-SAVOL`;
    document.getElementById("qTopicBadge").textContent = qObj.topic;
    document.getElementById("qText").textContent = qObj.q;

    for (let i = 0; i < 20; i++) {
      const d = document.getElementById(`dot-${i}`);
      d.classList.remove("current");
      if (i === currentIndex) d.classList.add("current");
    }

    const optsContainer = document.getElementById("optionsContainer");
    optsContainer.innerHTML = "";
    const letters = ["A", "B", "C", "D"];

    qObj.shuffledOptions.forEach((optText, idx) => {
      const btn = document.createElement("button");
      btn.className = "opt-btn";
      btn.innerHTML = `
        <span class="opt-letter">${letters[idx]}</span>
        <span class="opt-text">${optText}</span>
        <span class="opt-icon"></span>
      `;
      btn.addEventListener("click", () => selectOption(optText, btn));
      optsContainer.appendChild(btn);
    });
  }

  function selectOption(selectedText, clickedBtn) {
    if (locked) return;
    locked = true;

    const qObj = questions[currentIndex];
    const isCorrect = selectedText === qObj.answer;
    const allBtns = document.querySelectorAll(".opt-btn");
    allBtns.forEach(b => b.disabled = true);

    const card = document.getElementById("quizCard");
    const banner = document.getElementById("feedbackBanner");
    const currentDot = document.getElementById(`dot-${currentIndex}`);

    if (isCorrect) {
      correctCount++;
      streak++;
      clickedBtn.classList.add("is-correct");
      clickedBtn.querySelector(".opt-icon").textContent = "✔";
      currentDot.classList.add("done-ok");

      card.classList.add("flash-ok");
      banner.className = "feedback-banner ok show";
      banner.innerHTML = `<span>✅ Barakalla! To'g'ri javob!</span><span>+${streak > 1 ? streak + " 🔥" : "1"}</span>`;
      playTone("correct");
      triggerHaptic("success");
    } else {
      wrongCount++;
      streak = 0;
      clickedBtn.classList.add("is-wrong");
      clickedBtn.querySelector(".opt-icon").textContent = "✖";
      currentDot.classList.add("done-bad");

      allBtns.forEach(b => {
        if (b.querySelector(".opt-text").textContent === qObj.answer) {
          b.classList.add("is-correct");
          b.querySelector(".opt-icon").textContent = "✔";
        }
      });

      card.classList.add("flash-bad");
      banner.className = "feedback-banner bad show";
      banner.innerHTML = `<span>❌ Xato! To'g'ri javob: <strong>${qObj.answer}</strong></span>`;
      playTone("wrong");
      triggerHaptic("error");
    }

    updateStatsUI();

    setTimeout(() => {
      card.classList.remove("flash-ok", "flash-bad");
      currentIndex++;
      locked = false;
      renderCurrentQuestion();
    }, isCorrect ? 850 : 1400);
  }

  function updateStatsUI() {
    document.getElementById("statCorrect").textContent = correctCount;
    document.getElementById("statWrong").textContent = wrongCount;
    document.getElementById("statStreak").textContent = `${streak} 🔥`;

    const total = correctCount + wrongCount;
    const acc = total === 0 ? 100 : Math.round((correctCount / total) * 100);
    document.getElementById("statAcc").textContent = `${acc}%`;
  }

  function autoSaveParticipantResult() {
    if (currentAttemptSaved) return;
    const solved = correctCount + wrongCount;
    if (solved === 0) return;

    currentAttemptSaved = true;
    const studentName = document.getElementById("studentName").value.trim() || "Ishtirokchi";
    const accuracyPct = Math.round((correctCount / solved) * 100);
    const totalTestPct = Math.round((correctCount / 20) * 100);
    const grade = getGradeText(correctCount);

    const now = new Date();
    const dateStr = now.toLocaleDateString("uz-UZ", {
      month: "2-digit",
      day: "2-digit"
    }) + " " + now.toLocaleTimeString("uz-UZ", {
      hour: "2-digit",
      minute: "2-digit"
    });

    const recordId = Date.now() + "_" + Math.random().toString(36).substring(2, 7);
    lastSavedRecordId = recordId;

    const newEntry = {
      id: recordId,
      tgId: telegramUser.id || null,
      name: studentName,
      correct: correctCount,
      wrong: wrongCount,
      solved,
      accuracyPct,
      totalTestPct,
      timeSec: parseFloat(elapsedSec.toFixed(1)),
      grade,
      date: dateStr,
      timestamp: Date.now()
    };

    pushResultToCloud(newEntry);
  }

  function saveCurrentAttemptManually() {
    const solved = correctCount + wrongCount;
    if (solved === 0) {
      alert("Hozircha savol yechilmadi!");
      return;
    }
    if (currentAttemptSaved) {
      alert("Ushbu natija allaqachon reytingga saqlangan!");
      return;
    }
    autoSaveParticipantResult();
    renderLeaderboardTable();
  }

  function finishQuiz() {
    if (timerInterval) clearInterval(timerInterval);
    playTone("finish");
    triggerHaptic("success");

    autoSaveParticipantResult();

    const studentName = document.getElementById("studentName").value.trim() || "Ishtirokchi";
    const acc = Math.round((correctCount / 20) * 100);
    const grade = getGradeText(correctCount);

    document.getElementById("certNameInput").value = studentName;
    document.getElementById("sumName").textContent = studentName;
    document.getElementById("sumCorrect").textContent = `${correctCount} ta`;
    document.getElementById("sumWrong").textContent = `${wrongCount} ta`;
    document.getElementById("sumAcc").textContent = `${acc}% (${correctCount}/20)`;
    document.getElementById("sumTime").textContent = `${elapsedSec.toFixed(1)} soniya`;
    document.getElementById("sumGrade").textContent = grade;
    document.getElementById("resSubText").textContent =
      `${studentName}, siz 20 ta savoldan ${correctCount} tasiga (${acc}%) to'g'ri javob berdingiz!`;

    drawCertificate(studentName, correctCount, acc, elapsedSec.toFixed(1), grade);
    document.getElementById("resultModal").classList.add("active");
  }

  function shareResultToTelegram() {
    const studentName = document.getElementById("studentName").value.trim() || "Ishtirokchi";
    const acc = Math.round((correctCount / 20) * 100);
    const grade = getGradeText(correctCount);

    const shareText =
      `🏆 7-sinf Geografiya (3.6. Yer yuzi aholisi) onlayn testi!\n` +
      `👤 Ishtirokchi: ${studentName}\n` +
      `✅ To'g'ri javob: ${correctCount} / 20 ta (${acc}%)\n` +
      `⏱ Vaqt: ${elapsedSec.toFixed(1)} soniya\n` +
      `🎖 Daraja: ${grade}`;

    const shareUrl = `https://t.me/share/url?url=${encodeURIComponent(window.location.href)}&text=${encodeURIComponent(shareText)}`;
    if (tg && tg.openTelegramLink) {
      tg.openTelegramLink(shareUrl);
    } else {
      window.open(shareUrl, "_blank");
    }
  }

  /* =========================================================
     6. ONLAYN REYTING JADVALI VA EXCEL EKSPORT
     ========================================================= */
  function openLeaderboardModal() {
    syncFromCloudNow();
    renderLeaderboardTable();
    document.getElementById("leaderboardModal").classList.add("active");
  }

  function closeLeaderboardModal() {
    document.getElementById("leaderboardModal").classList.remove("active");
  }

  function escapeHtml(str) {
    return String(str || "")
      .replace(/&/g, "&amp;")
      .replace(/</g, "&lt;")
      .replace(/>/g, "&gt;")
      .replace(/"/g, "&quot;");
  }

  function renderLeaderboardTable() {
    const allList = getLocalLeaderboard();
    const searchVal = (document.getElementById("historySearchInput").value || "").toLowerCase().trim();
    const sortBy = document.getElementById("historySortSelect").value;

    document.getElementById("sumTotalPlayers").textContent = `${allList.length} ta`;
    if (allList.length === 0) {
      document.getElementById("sumAvgPercent").textContent = "0%";
      document.getElementById("sumBestScore").textContent = "-";
      document.getElementById("sumExcellentCount").textContent = "0 ta";
    } else {
      const avgPct = Math.round(allList.reduce((acc, item) => acc + (item.totalTestPct || 0), 0) / allList.length);
      const bestItem = [...allList].sort((a, b) => b.correct - a.correct || a.timeSec - b.timeSec)[0];
      const excellentCount = allList.filter(i => i.correct >= 18).length;

      document.getElementById("sumAvgPercent").textContent = `${avgPct}%`;
      document.getElementById("sumBestScore").textContent = `${bestItem.name} (${bestItem.totalTestPct}%)`;
      document.getElementById("sumExcellentCount").textContent = `${excellentCount} ta`;
    }

    let filtered = allList.filter(item => (item.name || "").toLowerCase().includes(searchVal));

    if (sortBy === "leaderboard" || sortBy === "correct_desc") {
      filtered.sort((a, b) => b.correct - a.correct || b.accuracyPct - a.accuracyPct || a.timeSec - b.timeSec);
    } else {
      filtered.sort((a, b) => (b.timestamp || 0) - (a.timestamp || 0));
    }

    const tbody = document.getElementById("historyTableBody");
    const emptyMsg = document.getElementById("emptyHistoryMsg");
    tbody.innerHTML = "";

    if (filtered.length === 0) {
      emptyMsg.style.display = "block";
      return;
    }
    emptyMsg.style.display = "none";

    filtered.forEach((item, idx) => {
      const tr = document.createElement("tr");

      let rankBadge = `<span style="font-weight:800; color:#94a3b8;">#${idx + 1}</span>`;
      if (idx === 0) rankBadge = `<span class="rank-medal rank-1">1</span>`;
      else if (idx === 1) rankBadge = `<span class="rank-medal rank-2">2</span>`;
      else if (idx === 2) rankBadge = `<span class="rank-medal rank-3">3</span>`;

      const testPctClass = item.totalTestPct >= 80 ? "pct-high" : item.totalTestPct >= 55 ? "pct-mid" : "pct-low";
      const accClass = item.accuracyPct >= 80 ? "pct-high" : item.accuracyPct >= 55 ? "pct-mid" : "pct-low";

      let gradeClass = "grade-2";
      if (item.correct >= 18) gradeClass = "grade-5";
      else if (item.correct >= 14) gradeClass = "grade-4";
      else if (item.correct >= 10) gradeClass = "grade-3";

      tr.innerHTML = `
        <td>${rankBadge}</td>
        <td style="font-weight:800; color:#fff;">${escapeHtml(item.name)}</td>
        <td><strong style="color:#34d399; font-size:14.5px;">${item.correct} ta</strong> <span style="color:#94a3b8; font-size:11px;">(${item.solved}/20)</span></td>
        <td><strong style="color:#f87171;">${item.wrong} ta</strong></td>
        <td><span class="pct-badge ${testPctClass}">${item.totalTestPct}%</span></td>
        <td><span class="pct-badge ${accClass}">${item.accuracyPct}%</span></td>
        <td style="color:#fbbf24; font-weight:700;">${item.timeSec} s</td>
        <td><span class="grade-pill ${gradeClass}">${escapeHtml(item.grade)}</span></td>
        <td style="color:#94a3b8; font-size:11.5px;">${escapeHtml(item.date)}</td>
      `;
      tbody.appendChild(tr);
    });
  }

  function clearAllHistory() {
    if (confirm("Mahalliy ro'yxatni tozalamoqchimisiz?")) {
      saveLocalLeaderboard([]);
      renderLeaderboardTable();
    }
  }

  function exportHistoryCSV() {
    const list = getLocalLeaderboard();
    if (list.length === 0) {
      alert("Yuklab olish uchun natijalar yo'q!");
      return;
    }

    const headers = ["O'rin", "Ishtirokchi", "To'g'ri javob", "Xato javob", "Test Foizi (%)", "Aniqlik (%)", "Vaqt (s)", "Baho", "Sana"];
    const sorted = [...list].sort((a, b) => b.correct - a.correct || a.timeSec - b.timeSec);

    const rows = sorted.map((item, idx) => [
      idx + 1,
      `"${(item.name || "").replace(/"/g, '""')}"`,
      item.correct,
      item.wrong,
      `${item.totalTestPct}%`,
      `${item.accuracyPct}%`,
      item.timeSec,
      `"${item.grade}"`,
      `"${item.date}"`
    ]);

    const csvContent = "\uFEFF" + [headers.join(";"), ...rows.map(r => r.join(";"))].join("\r\n");
    const blob = new Blob([csvContent], { type: "text/csv;charset=utf-8;" });
    const url = URL.createObjectURL(blob);
    const a = document.createElement("a");
    a.href = url;
    a.download = `Telegram_Reyting_7sinf_Geografiya_${new Date().toISOString().slice(0, 10)}.csv`;
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
  }

  /* =========================================================
     7. SERTIFIKAT CHIZISH VA JAVOBLAR KALITI
     ========================================================= */
  function updateCertName() {
    const newName = document.getElementById("certNameInput").value.trim() || "Ishtirokchi";
    document.getElementById("studentName").value = newName;
    document.getElementById("sumName").textContent = newName;
    saveLocalSettings();

    if (lastSavedRecordId) {
      const list = getLocalLeaderboard();
      const target = list.find(item => item.id === lastSavedRecordId);
      if (target) {
        target.name = newName;
        pushResultToCloud(target);
      }
    }

    const acc = Math.round((correctCount / 20) * 100);
    const grade = getGradeText(correctCount);
    drawCertificate(newName, correctCount, acc, elapsedSec.toFixed(1), grade);
  }

  function drawCertificate(name, correct, acc, timeStr, grade) {
    const canvas = document.getElementById("certCanvas");
    const ctx = canvas.getContext("2d");
    const W = canvas.width;
    const H = canvas.height;

    ctx.clearRect(0, 0, W, H);

    const bgGrad = ctx.createLinearGradient(0, 0, W, H);
    bgGrad.addColorStop(0, "#071124");
    bgGrad.addColorStop(0.5, "#0f223d");
    bgGrad.addColorStop(1, "#071124");
    ctx.fillStyle = bgGrad;
    ctx.fillRect(0, 0, W, H);

    const goldGrad = ctx.createLinearGradient(0, 0, W, H);
    goldGrad.addColorStop(0, "#fde047");
    goldGrad.addColorStop(0.5, "#d97706");
    goldGrad.addColorStop(1, "#fef08a");

    ctx.strokeStyle = goldGrad;
    ctx.lineWidth = 8;
    ctx.strokeRect(28, 28, W - 56, H - 56);

    ctx.strokeStyle = "rgba(253, 224, 71, 0.45)";
    ctx.lineWidth = 2;
    ctx.strokeRect(44, 44, W - 88, H - 88);

    ctx.fillStyle = "#38bdf8";
    ctx.font = 'bold 20px "Segoe UI", sans-serif';
    ctx.textAlign = "center";
    ctx.fillText("7-SINF GEOGRAFIYA • TELEGRAM ONLAYN OLIMPIADA SERTIFIKATI", W / 2, 105);

    ctx.fillStyle = goldGrad;
    ctx.font = '900 62px "Segoe UI", Georgia, serif';
    ctx.fillText("SERTIFIKAT", W / 2, 180);

    ctx.fillStyle = "#cbd5e1";
    ctx.font = 'italic 22px "Segoe UI", sans-serif';
    ctx.fillText("Ushbu sertifikat egasi:", W / 2, 245);

    ctx.fillStyle = "#ffffff";
    ctx.font = '900 50px "Segoe UI", sans-serif';
    ctx.shadowColor = "rgba(56, 189, 248, 0.6)";
    ctx.shadowBlur = 18;
    ctx.fillText(name.toUpperCase(), W / 2, 320);
    ctx.shadowBlur = 0;

    ctx.strokeStyle = "rgba(253, 224, 71, 0.6)";
    ctx.lineWidth = 2;
    ctx.beginPath();
    ctx.moveTo(W / 2 - 280, 340);
    ctx.lineTo(W / 2 + 280, 340);
    ctx.stroke();

    ctx.fillStyle = "#e2e8f0";
    ctx.font = '600 23px "Segoe UI", sans-serif';
    ctx.fillText("7-sinf Geografiya darsligining «3.6. Yer yuzi aholisi va uning tabiatga ta'siri»", W / 2, 395);
    ctx.fillText("mavzusi bo'yicha Telegram onlayn test sinovini muvaffaqiyatli", W / 2, 430);
    ctx.fillText("yakunlab, umumiy reytingda quyidagi natijani qayd etgani uchun berildi:", W / 2, 465);

    const boxes = [
      { label: "NATIJA (FOIZ)", val: `${correct} / 20 (${acc}%)`, x: 240 },
      { label: "SARFLANGAN VAQT", val: `${timeStr} soniya`, x: 600 },
      { label: "DARAJA / BAHO", val: grade, x: 960 }
    ];

    boxes.forEach(b => {
      ctx.fillStyle = "rgba(30, 41, 59, 0.85)";
      ctx.strokeStyle = "rgba(253, 224, 71, 0.45)";
      ctx.lineWidth = 2;
      ctx.beginPath();
      ctx.roundRect(b.x - 155, 510, 310, 95, 14);
      ctx.fill();
      ctx.stroke();

      ctx.fillStyle = "#94a3b8";
      ctx.font = 'bold 14px "Segoe UI", sans-serif';
      ctx.fillText(b.label, b.x, 542);

      ctx.fillStyle = "#fde047";
      ctx.font = '900 21px "Segoe UI", sans-serif';
      ctx.fillText(b.val, b.x, 580);
    });

    const todayStr = new Date().toLocaleDateString("uz-UZ", {
      year: "numeric",
      month: "2-digit",
      day: "2-digit"
    });

    ctx.fillStyle = "#cbd5e1";
    ctx.font = 'bold 18px "Segoe UI", sans-serif';
    ctx.fillText(`Sana: ${todayStr}`, 260, 730);
    ctx.fillText("Geografiya fani o'qituvchisi", 940, 730);

    ctx.save();
    ctx.translate(W / 2, 715);
    ctx.fillStyle = goldGrad;
    ctx.beginPath();
    ctx.arc(0, 0, 50, 0, Math.PI * 2);
    ctx.fill();
    ctx.fillStyle = "#071124";
    ctx.font = '900 15px "Segoe UI", sans-serif';
    ctx.fillText("★ GEOGRAFIYA ★", 0, -2);
    ctx.font = 'bold 13px "Segoe UI", sans-serif';
    ctx.fillText("7-SINF", 0, 16);
    ctx.restore();
  }

  function downloadCertificatePNG() {
    const canvas = document.getElementById("certCanvas");
    const link = document.createElement("a");
    const name = (document.getElementById("certNameInput").value || "Ishtirokchi").replace(/[^a-zA-Z0-9_Ѐ-ӿ-]/g, "_");
    link.download = `Sertifikat_7sinf_Geografiya_${name}.png`;
    link.href = canvas.toDataURL("image/png");
    link.click();
  }

  function openQAModal() {
    const container = document.getElementById("qaListContainer");
    container.innerHTML = "";
    const letters = ["A", "B", "C", "D"];

    MASTER_QUESTIONS.forEach((item, index) => {
      const div = document.createElement("div");
      div.className = "qa-item";
      const optsHtml = item.options.map((opt, i) => {
        const isAns = opt === item.answer;
        return `<li class="${isAns ? "correct-ans" : ""}">${letters[i]}) ${opt} ${isAns ? " ✔" : ""}</li>`;
      }).join("");

      div.innerHTML = `
        <div class="qa-item-q">${index + 1}. ${item.q}</div>
        <ul class="qa-item-opts">${optsHtml}</ul>
      `;
      container.appendChild(div);
    });
    document.getElementById("qaModal").classList.add("active");
  }

  function closeQAModal() {
    document.getElementById("qaModal").classList.remove("active");
  }

  // Sahifa yuklanganda Telegram SDK, Bulut Xona va Testni ishga tushirish
  window.addEventListener("DOMContentLoaded", () => {
    initTelegramMiniApp();
    loadLocalSettings();
    ensureCloudRoomInitialized();
    startQuiz();

    // Har 6 soniyada boshqa o'quvchilarning yangi natijalarini onlayn bazadan tortib yangilab turadi
    setInterval(syncFromCloudNow, 6000);
  });
</script>
</body>
</html>
