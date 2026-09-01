<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Super Mario Road - Arcade Deluxe Edition</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@600;700;800&family=Outfit:wght@600;700;800;900&display=swap');

        * {
            box-sizing: border-box;
            user-select: none;
            -webkit-user-select: none;
            -webkit-touch-callout: none;
            margin: 0;
            padding: 0;
        }
        body {
            background: radial-gradient(circle at 50% 20%, #1e1b4b 0%, #090d16 50%, #030712 100%);
            font-family: 'Outfit', -apple-system, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #f8fafc;
            padding: 12px;
            overflow-x: hidden;
        }
        .casino-cabinet {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-radius: 24px;
            padding: 18px;
            box-shadow: 0 30px 80px rgba(0,0,0,0.9), 0 0 40px rgba(99, 102, 241, 0.2), inset 0 1px 1px rgba(255,255,255,0.1);
            border: 1px solid rgba(255, 255, 255, 0.08);
            display: flex;
            flex-direction: column;
            gap: 12px;
            width: 100%;
            max-width: 940px;
            position: relative;
        }
        .shake {
            animation: shakeScreen 0.4s cubic-bezier(.36,.07,.19,.97) both;
        }
        @keyframes shakeScreen {
            10%, 90% { transform: translate3d(-3px, 0, 0); }
            20%, 80% { transform: translate3d(5px, 0, 0); }
            30%, 50%, 70% { transform: translate3d(-6px, 0, 0); }
            40%, 60% { transform: translate3d(6px, 0, 0); }
        }

        .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        .brand-title {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 20px;
            font-weight: 900;
            font-family: 'Fredoka', cursive;
            color: #ef4444;
            text-shadow: 0 0 20px rgba(239, 68, 68, 0.6);
            letter-spacing: 0.5px;
        }
        .brand-title span { 
            color: #fbbf24; 
            text-shadow: 0 0 20px rgba(251, 191, 36, 0.7); 
        }
        
        .top-actions {
            display: flex;
            gap: 6px;
            align-items: center;
            flex-wrap: wrap;
        }
        .btn-toggle, .lang-select {
            background: rgba(30, 41, 59, 0.7);
            color: #94a3b8;
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 6px 12px;
            border-radius: 10px;
            font-size: 12px;
            font-weight: 700;
            cursor: pointer;
            outline: none;
            touch-action: manipulation;
            transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(8px);
        }
        .btn-toggle:hover, .lang-select:hover {
            background: rgba(51, 65, 85, 0.9);
            color: #fff;
            border-color: rgba(255, 255, 255, 0.2);
            transform: translateY(-1px);
        }
        .btn-toggle.active {
            background: linear-gradient(135deg, #3b82f6, #1d4ed8);
            color: #fff;
            border-color: #60a5fa;
            box-shadow: 0 0 16px rgba(59, 130, 246, 0.6);
        }
        .lang-select { color: #fbbf24; font-weight: 800; }

        .world-badge {
            background: linear-gradient(135deg, #3b82f6, #1d4ed8);
            color: #fff;
            padding: 5px 12px;
            border-radius: 10px;
            font-weight: 900;
            font-size: 12px;
            box-shadow: 0 0 18px rgba(59, 130, 246, 0.5);
            display: inline-flex;
            align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.3);
            letter-spacing: 0.5px;
        }

        .history-bar {
            display: flex;
            gap: 6px;
            align-items: center;
            background: rgba(10, 15, 29, 0.75);
            padding: 6px 12px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.06);
            min-height: 36px;
            overflow-x: auto;
            white-space: nowrap;
        }
        .history-label {
            font-size: 10px;
            font-weight: 800;
            color: #64748b;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        .history-badge {
            padding: 3px 10px;
            border-radius: 8px;
            font-size: 11.5px;
            font-weight: 900;
            animation: popIn 0.3s ease;
            flex-shrink: 0;
        }
        .badge-win { 
            background: rgba(34, 197, 94, 0.15); 
            color: #4ade80; 
            border: 1px solid rgba(34, 197, 94, 0.4); 
            box-shadow: 0 0 10px rgba(34, 197, 94, 0.2);
        }
        .badge-loss { 
            background: rgba(239, 68, 68, 0.15); 
            color: #f87171; 
            border: 1px solid rgba(239, 68, 68, 0.4); 
            box-shadow: 0 0 10px rgba(239, 68, 68, 0.2);
        }

        @keyframes popIn {
            0% { transform: scale(0.5); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }
        .stat-card {
            background: linear-gradient(180deg, rgba(30, 41, 59, 0.6) 0%, rgba(15, 23, 42, 0.8) 100%);
            border: 1px solid rgba(255, 255, 255, 0.08);
            padding: 8px 12px;
            border-radius: 14px;
            display: flex;
            flex-direction: column;
            gap: 2px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
            position: relative;
            overflow: hidden;
        }
        .stat-card::before {
            content: '';
            position: absolute;
            top: 0; left: 0; width: 100%; height: 2px;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
        }
        .stat-card .label { 
            font-size: 9.5px; 
            color: #94a3b8; 
            font-weight: 800; 
            text-transform: uppercase; 
            letter-spacing: 0.5px;
        }
        .stat-card .value { 
            font-size: 17px; 
            font-weight: 900; 
            font-variant-numeric: tabular-nums; 
        }
        .val-gold { color: #fbbf24; text-shadow: 0 0 15px rgba(251, 191, 36, 0.4); }
        .val-green { color: #22c55e; text-shadow: 0 0 15px rgba(34, 197, 94, 0.4); }
        .val-blue { color: #38bdf8; text-shadow: 0 0 15px rgba(56, 189, 248, 0.4); }
        .val-shield { color: #c084fc; text-shadow: 0 0 15px rgba(192, 132, 252, 0.4); }

        .screen-container {
            position: relative;
            border-radius: 16px;
            overflow: hidden;
            border: 2px solid rgba(255, 255, 255, 0.12);
            width: 100%;
            box-shadow: inset 0 0 35px rgba(0,0,0,0.8), 0 10px 30px rgba(0,0,0,0.5);
        }
        canvas {
            display: block;
            width: 100%;
            height: auto;
            aspect-ratio: 850 / 290;
        }

        .bonus-overlay {
            display: none;
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(8, 12, 22, 0.95);
            backdrop-filter: blur(12px);
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 16px;
            z-index: 20;
            animation: fadeIn 0.3s ease;
        }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        .bonus-title {
            font-size: 18px;
            font-weight: 900;
            color: #fbbf24;
            text-shadow: 0 0 20px rgba(251, 191, 36, 0.8);
            text-align: center;
            padding: 0 16px;
            letter-spacing: 0.5px;
        }
        .chests-container {
            display: flex;
            gap: 20px;
        }
        .chest-card {
            background: linear-gradient(180deg, #1e293b 0%, #0f172a 100%);
            border: 2px solid #eab308;
            border-radius: 18px;
            width: 90px;
            height: 105px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.25s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 10px 30px rgba(0,0,0,0.7), 0 0 20px rgba(234, 179, 8, 0.25);
        }
        .chest-card:hover {
            transform: translateY(-10px) scale(1.08);
            border-color: #fef08a;
            box-shadow: 0 15px 35px rgba(234, 179, 8, 0.6);
        }
        .chest-icon { font-size: 42px; filter: drop-shadow(0 4px 10px rgba(0,0,0,0.5)); }
        .chest-multiplier {
            font-size: 17px;
            font-weight: 900;
            display: none;
        }
        .bonus-actions {
            display: flex;
            gap: 10px;
            margin-top: 4px;
        }
        .btn-chest-cashout {
            background: linear-gradient(135deg, #f59e0b, #d97706);
            color: #000;
            font-weight: 900;
            padding: 10px 24px;
            border-radius: 12px;
            border: none;
            font-size: 14px;
            cursor: pointer;
            box-shadow: 0 4px 20px rgba(245, 158, 11, 0.5);
            transition: all 0.2s;
        }
        .btn-chest-cashout:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(245, 158, 11, 0.7);
        }

        .status-banner {
            background: rgba(10, 15, 29, 0.85);
            padding: 10px;
            border-radius: 14px;
            text-align: center;
            font-weight: 800;
            font-size: 14.5px;
            min-height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: inset 0 2px 8px rgba(0,0,0,0.4);
        }

        .control-panel {
            background: linear-gradient(180deg, rgba(20, 28, 48, 0.8) 0%, rgba(10, 15, 29, 0.95) 100%);
            border: 1px solid rgba(255, 255, 255, 0.08);
            padding: 14px;
            border-radius: 18px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
        }
        .inputs-row {
            display: flex;
            gap: 12px;
            width: 100%;
            justify-content: space-between;
        }
        .control-field { display: flex; flex-direction: column; gap: 4px; flex: 1; }
        .control-field label { 
            font-size: 10px; 
            color: #94a3b8; 
            font-weight: 800; 
            text-transform: uppercase; 
            letter-spacing: 0.5px;
        }
        .bet-input-box { display: flex; gap: 4px; width: 100%; }
        input, select {
            background: rgba(30, 41, 59, 0.8);
            border: 1px solid rgba(255, 255, 255, 0.12);
            color: #fff;
            padding: 9px 12px;
            border-radius: 10px;
            font-size: 14px;
            font-weight: 800;
            outline: none;
            text-align: center;
            width: 100%;
            transition: all 0.2s;
        }
        input:focus, select:focus {
            border-color: #3b82f6;
            box-shadow: 0 0 12px rgba(59, 130, 246, 0.4);
        }

        .btn-quick {
            background: rgba(30, 41, 59, 0.8);
            border: 1px solid rgba(255, 255, 255, 0.12);
            color: #94a3b8;
            padding: 0 10px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 800;
            cursor: pointer;
            transition: all 0.15s;
        }
        .btn-quick:hover:not(:disabled) { 
            background: #334155; 
            color: #fff; 
            border-color: rgba(255, 255, 255, 0.25);
        }

        .action-buttons {
            display: flex;
            gap: 8px;
            width: 100%;
        }
        .btn-action {
            padding: 14px;
            border-radius: 12px;
            font-size: 14.5px;
            font-weight: 900;
            border: none;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 6px;
            white-space: nowrap;
            flex: 1;
            touch-action: manipulation;
            transition: all 0.2s ease-in-out;
            letter-spacing: 0.4px;
        }
        .btn-bet { 
            background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%); 
            color: #fff; 
            box-shadow: 0 4px 20px rgba(59, 130, 246, 0.4), inset 0 1px 1px rgba(255,255,255,0.3);
            border: 1px solid rgba(255,255,255,0.2);
        }
        .btn-bet:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(59, 130, 246, 0.6);
        }
        .btn-next { 
            background: linear-gradient(135deg, #22c55e 0%, #15803d 100%); 
            color: #fff; 
            box-shadow: 0 4px 20px rgba(34, 197, 94, 0.4), inset 0 1px 1px rgba(255,255,255,0.3);
            border: 1px solid rgba(255,255,255,0.2);
        }
        .btn-next:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(34, 197, 94, 0.6);
        }
        .btn-cashout { 
            background: linear-gradient(135deg, #fbbf24 0%, #d97706 100%); 
            color: #000; 
            box-shadow: 0 4px 20px rgba(245, 158, 11, 0.5), inset 0 1px 1px rgba(255,255,255,0.4);
            border: 1px solid rgba(255,255,255,0.3);
        }
        .btn-cashout:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(245, 158, 11, 0.7);
        }
        .btn-warp {
            background: linear-gradient(135deg, #c084fc 0%, #7e22ce 100%); 
            color: #fff;
            box-shadow: 0 4px 20px rgba(168, 85, 247, 0.5), inset 0 1px 1px rgba(255,255,255,0.3);
            border: 1px solid rgba(255,255,255,0.2);
            animation: pulseBtn 1.2s infinite;
        }
        @keyframes pulseBtn {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.03); }
        }
        .btn-action:disabled, .btn-quick:disabled {
            background: rgba(30, 41, 59, 0.4) !important;
            color: #475569 !important;
            box-shadow: none !important;
            cursor: not-allowed;
            animation: none !important;
            transform: none !important;
            border-color: transparent !important;
        }

        /* Modal */
        .modal-overlay {
            display: none;
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.85);
            backdrop-filter: blur(8px);
            justify-content: center;
            align-items: center;
            z-index: 100;
            padding: 12px;
        }
        .modal-content {
            background: #0f172a;
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 20px;
            width: 100%;
            max-width: 540px;
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 14px;
            box-shadow: 0 25px 60px rgba(0,0,0,0.9);
        }
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
            padding-bottom: 10px;
        }
        .modal-header h3 { font-size: 17px; color: #fbbf24; font-weight: 800; }
        .btn-close { background: transparent; border: none; color: #64748b; font-size: 24px; cursor: pointer; }
        .modal-body { font-size: 13px; line-height: 1.6; color: #94a3b8; display: flex; flex-direction: column; gap: 10px; }
        .rtp-box { 
            background: rgba(10, 15, 29, 0.8); 
            border-left: 4px solid #3b82f6; 
            padding: 10px 14px; 
            border-radius: 8px; 
            color: #f8fafc; 
        }
        .rtp-box strong { color: #38bdf8; }
        .rule-list { padding-left: 20px; }
        .rule-list li { margin-bottom: 4px; }

        @media (min-width: 768px) {
            .control-panel { flex-direction: row; align-items: center; gap: 14px; }
            .inputs-row { width: auto; justify-content: flex-start; gap: 14px; }
            .action-buttons { flex: 1; justify-content: flex-end; }
        }
    </style>
</head>
<body>

<div class="casino-cabinet" id="cabinet">
    <div class="top-bar">
        <div class="brand-title">
            🍄 SUPER MARIO <span>ROAD PRO</span>
            <div class="world-badge" id="world-badge">WORLD 1-1</div>
        </div>
        <div class="top-actions">
            <select class="lang-select" id="lang-select">
                <option value="ka">🇬🇪 KA</option>
                <option value="en" selected>🇬🇧 EN</option>
                <option value="ru">🇷🇺 RU</option>
                <option value="es">🇪🇸 ES</option>
            </select>
            <button class="btn-toggle" id="turbo-btn">⚡ Turbo: OFF</button>
            <button class="btn-toggle" id="sound-btn">🔊 Sound: ON</button>
            <button class="btn-toggle" id="rules-btn">📖 Rules</button>
        </div>
    </div>

    <div class="history-bar" id="history-bar">
        <span class="history-label" id="lbl-history">HISTORY:</span>
        <span style="font-size: 10px; color: #475569;" id="history-empty">No rounds yet</span>
    </div>

    <div class="stats-grid">
        <div class="stat-card">
            <span class="label" id="lbl-balance">BALANCE</span>
            <span class="value val-gold" id="balance-display">$1000.00</span>
        </div>
        <div class="stat-card">
            <span class="label" id="lbl-checkpoint">GUARANTEED</span>
            <span class="value val-shield" id="checkpoint-display">$0.00</span>
        </div>
        <div class="stat-card">
            <span class="label" id="lbl-mult">MULT</span>
            <span class="value val-blue" id="mult-display">1.00x</span>
        </div>
        <div class="stat-card">
            <span class="label" id="lbl-win">CURRENT WIN</span>
            <span class="value val-green" id="win-display">$0.00</span>
        </div>
    </div>

    <div class="screen-container">
        <canvas id="gameCanvas" width="850" height="290"></canvas>
        
        <div class="bonus-overlay" id="bonus-overlay">
            <div class="bonus-title" id="bonus-title">🎁 PICK A CHEST OR CASH OUT!</div>
            <div class="chests-container" id="chests-container">
                <div class="chest-card" onclick="openMysteryChest(0)">
                    <span class="chest-icon">📦</span>
                    <span class="chest-multiplier" id="chest-mult-0"></span>
                </div>
                <div class="chest-card" onclick="openMysteryChest(1)">
                    <span class="chest-icon">📦</span>
                    <span class="chest-multiplier" id="chest-mult-1"></span>
                </div>
                <div class="chest-card" onclick="openMysteryChest(2)">
                    <span class="chest-icon">📦</span>
                    <span class="chest-multiplier" id="chest-mult-2"></span>
                </div>
            </div>
            <div class="bonus-actions">
                <button class="btn-chest-cashout" id="btn-bonus-cashout" onclick="cashOutFromBonus()">CASH OUT NOW</button>
            </div>
        </div>
    </div>

    <div class="status-banner" id="status-msg">Place your bet and start the game</div>

    <div class="control-panel">
        <div class="inputs-row">
            <div class="control-field">
                <label for="bet-input" id="lbl-bet">BET ($)</label>
                <div class="bet-input-box">
                    <input type="number" id="bet-input" value="10" min="1" max="1000">
                    <button class="btn-quick" id="btn-half">1/2</button>
                    <button class="btn-quick" id="btn-double">2X</button>
                    <button class="btn-quick" id="btn-max">MAX</button>
                </div>
            </div>
            <div class="control-field">
                <label for="mines-select" id="lbl-mines">DIFFICULTY</label>
                <select id="mines-select">
                    <option value="1" id="opt-m1">Easy (High Win Rate)</option>
                    <option value="2" id="opt-m2" selected>Medium (Balanced)</option>
                    <option value="3" id="opt-m3">Hard (Extreme X)</option>
                </select>
            </div>
        </div>

        <div class="action-buttons">
            <button class="btn-action btn-bet" id="bet-btn">START (BET)</button>
            <button class="btn-action btn-next" id="next-btn" disabled>NEXT ➡️</button>
            <button class="btn-action btn-warp" id="warp-btn" style="display:none;">WARP 🚀</button>
            <button class="btn-action btn-cashout" id="cashout-btn" disabled>CASH OUT</button>
        </div>
    </div>
</div>

<div class="modal-overlay" id="rules-modal">
    <div class="modal-content">
        <div class="modal-header">
            <h3 id="modal-title">Rules & Multipliers</h3>
            <button class="btn-close" id="close-modal">&times;</button>
        </div>
        <div class="modal-body" id="modal-body"></div>
    </div>
</div>

<script>
const casinoMultiplierCurves = {
    1: {
        1: [1.06, 1.15, 1.28, 1.45, 1.68, 1.98, 2.40, 3.00, 3.80, 5.00],
        2: [6.50, 8.50, 11.50, 15.50, 21.00, 29.00, 40.00, 55.00, 75.00, 100.00],
        3: [130.00, 175.00, 240.00, 330.00, 460.00, 650.00, 900.00, 1300.00, 1900.00, 2800.00]
    },
    2: {
        1: [1.18, 1.45, 1.85, 2.45, 3.35, 4.70, 6.80, 10.00, 15.00, 24.00],
        2: [32.00, 45.00, 65.00, 95.00, 140.00, 210.00, 320.00, 480.00, 750.00, 1200.00],
        3: [1600.00, 2300.00, 3400.00, 5000.00, 7500.00, 11500.00, 18000.00, 28000.00, 45000.00, 75000.00]
    },
    3: {
        1: [1.45, 2.20, 3.40, 5.50, 9.00, 15.00, 26.00, 45.00, 80.00, 150.00],
        2: [250.00, 420.00, 750.00, 1350.00, 2500.00, 4800.00, 9200.00, 18000.00, 35000.00, 70000.00],
        3: [110000.00, 180000.00, 300000.00, 500000.00, 850000.00, 1500000.00, 2600000.00, 4500000.00, 7500000.00, 12000000.00]
    }
};

const translations = {
    en: {
        currency: "$",
        rulesBtn: "📖 Rules",
        history: "HISTORY:",
        noHistory: "No rounds yet",
        balance: "BALANCE",
        checkpoint: "GUARANTEED",
        mult: "MULT",
        win: "WIN",
        betLabel: "BET ($)",
        minesLabel: "DIFFICULTY",
        m1: "Easy (High Win Rate)",
        m2: "Medium (Balanced)",
        m3: "Hard (Extreme X)",
        startBtn: "START (BET)",
        nextBtn: "NEXT ➡️",
        cashoutBtn: "CASH OUT",
        readyMsg: "Place your bet and start the game",
        openingMsg: (w) => `${w}: Jumping to Block 1...`,
        worldEnteredMsg: (w, nextWin, nextMult, curr) => `Entered ${w}! Multipliers ready. Press NEXT for <strong style="color:#38bdf8;">${curr}${nextWin}</strong> (${nextMult}x) or Cash Out!`,
        loseMsgZero: (amt, curr) => `Poison Mushroom on Block 1! ☠️ Lost ${curr}${amt}`,
        loseMsgGuaranteed: (amt, curr) => `Poison Mushroom! ☠️ But you keep locked base GUARANTEE: +${curr}${amt}! 🛡️`,
        winMsg: (curWin, curMult, nextWin, nextMult, curr) => `Take <strong style="color:#fbbf24;">${curr}${curWin}</strong> (${curMult}x) or risk for <strong style="color:#38bdf8;">${curr}${nextWin}</strong> (${nextMult}x)?`,
        flagRunMsg: "🎉 All 10 Blocks Cleared! Pick a chest or Cash Out!",
        chestPrompt: (mult) => `🎁 3 CHESTS: 1x [${mult}X], 1x [1X], 1x [☠️ MUSHROOM]`,
        chestWon: (boost, amt, curr) => `🌟 BOOM! +${boost}X BONUS! Potential win: <strong style="color:#fbbf24;">${curr}${amt}</strong>!`,
        chestSafe: (amt, curr) => `👍 Safe Pass (1X)! Potential win: <strong style="color:#fbbf24;">${curr}${amt}</strong>!`,
        chestLostZero: (curr, amt) => `☠️ Poison Mushroom in chest! Lost ${curr}${amt}`,
        chestLostGuaranteed: (curr, amt) => `☠️ Poison Mushroom! Retained locked Guaranteed: +${curr}${amt}! 🛡️`,
        worldClearMsg: (w, win, curr) => `🏰 ${w} Cleared! Take <strong style="color:#fbbf24;">${curr}${win}</strong> or Warp!`,
        cashedOutMsg: (amt, mult, curr) => `Cashed out: +${curr}${amt} (${mult}x) 💰`,
        allClearedMsg: "👑 Legendary Victory! Completed all worlds! 🏆",
        invalidBet: "Invalid bet or balance!",
        warpBtn: (nextW, curr, win) => `Enter World ${nextW} 🚀`,
        modalTitle: "Super Mario Worlds - Rules & Multipliers",
        modalRtp: "Theoretical RTP: 97.00% | House Edge: 3.00%",
        modalRules: [
            "<strong>Easy Mode:</strong> Lower risk of mushrooms, steady multiplier growth up to 2,800x.",
            "<strong>Medium Mode:</strong> Balanced risk & reward curve up to 75,000x.",
            "<strong>Hard Mode:</strong> High risk of losing on every step, with extreme multipliers up to 12,000,000x!",
            "<strong>Real Risk from Block 1:</strong> Loss chance scales with difficulty directly from the first step.",
            "<strong>Guaranteed Checkpoint:</strong> Clearing World 1 locks your base win. Failing in World 2 still awards this guarantee."
        ]
    },
    ka: {
        currency: "₾",
        rulesBtn: "📖 წესები",
        history: "ისტორია:",
        noHistory: "რაუნდები არ არის",
        balance: "ბალანსი",
        checkpoint: "გარანტირებული",
        mult: "მამრავლი",
        win: "მოგება",
        betLabel: "ფსონი (₾)",
        minesLabel: "სირთულე",
        m1: "მარტივი (მაღალი შანსი)",
        m2: "საშუალო (ბალანსირებული)",
        m3: "რთული (ექსტრემალური X)",
        startBtn: "დაწყება (BET)",
        nextBtn: "შემდეგი ➡️",
        cashoutBtn: "გატანა (CASH OUT)",
        readyMsg: "დააყენეთ ფსონი და დაიწყეთ თამაში",
        openingMsg: (w) => `${w}: მარიო ხსნის პირველ ბლოკს...`,
        worldEnteredMsg: (w, nextWin, nextMult, curr) => `${w}-ში ხართ! 10-ვე მამრავლი მზადაა. დააჭირეთ „შემდეგი“-ს <strong style="color:#38bdf8;">${nextWin} ${curr}</strong>-ისთვის (${nextMult}x) ან გაიტანეთ!`,
        loseMsgZero: (amt, curr) => `საწამლავი სოკო პირველსავე ბლოკზე! ☠️ წააგეთ ${amt} ${curr}`,
        loseMsgGuaranteed: (amt, curr) => `საწამლავი სოკო! ☠️ მაგრამ დაგრჩათ გარანტირებული მოგება: +${amt} ${curr}! 🛡️`,
        winMsg: (curWin, curMult, nextWin, nextMult, curr) => `გაიტანეთ <strong style="color:#fbbf24;">${curWin} ${curr}</strong> (${curMult}x) ან გარისკეთ <strong style="color:#38bdf8;">${nextWin} ${curr}</strong>-ისთვის (${nextMult}x)`,
        flagRunMsg: "🎉 10-ვე ბლოკი გავლილია! აირჩიეთ ყუთი ან გაიტანეთ მოგება!",
        chestPrompt: (mult) => `🎁 3 ყუთი: 1x [${mult}X], 1x [1X], 1x [☠️ სოკო]`,
        chestWon: (boost, amt, curr) => `🌟 ბუუმ! +${boost}X ბონუსი! მიმდინარე მოგება: <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestSafe: (amt, curr) => `👍 უსაფრთხო (1X)! მოგება: <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestLostZero: (curr, amt) => `☠️ ყუთში აღმოჩნდა საწამლავი სოკო! წააგეთ ${amt} ${curr}`,
        chestLostGuaranteed: (curr, amt) => `☠️ სოკო ყუთში! მაგრამ შეინარჩუნეთ დაკეტილი გარანტირებული: +${amt} ${curr}! 🛡️`,
        worldClearMsg: (w, win, curr) => `🏰 ${w} გავლილია! გაიტანეთ <strong style="color:#fbbf24;">${win} ${curr}</strong> ან გადადით შემდეგ World-ში!`,
        cashedOutMsg: (amt, mult, curr) => `გატანილია: +${amt} ${curr} (${mult}x) 💰`,
        allClearedMsg: "👑 ლეგენდარული გამარჯვება! მთელი თამაში დაიხურა! 🏆",
        invalidBet: "არასწორი ფსონი!",
        warpBtn: (nextW, curr, win) => `World ${nextW}-ში გადასვლა 🚀`,
        modalTitle: "Super Mario Worlds - წესები & მამრავლები",
        modalRtp: "თეორიული RTP: 97.00% | House Edge: 3.00%",
        modalRules: [
            "<strong>მარტივი რეჟიმი:</strong> სოკოს დაბალი შანსი, სტაბილური ზრდა 2,800x-მდე.",
            "<strong>საშუალო რეჟიმი:</strong> ბალანსირებული რისკი და მამრავლები 75,000x-მდე.",
            "<strong>რთული რეჟიმი:</strong> მაღალი წაგების რისკი ყოველ ნაბიჯზე, მაგრამ გიგანტური X 12,000,000x-მდე!",
            "<strong>რისკი 1-ლი ბლოკიდანვე:</strong> სოკო შეიძლება იყოს პირველსავე ნაბიჯზე არჩეული სირთულის მიხედვით.",
            "<strong>ჩაკეტილი Checkpoint:</strong> 1-ლი ტურის დახურვისას იკეტება ბაზური მოგება, რაც გარანტირებულად გრჩებათ მე-2 ტურში წაგების შემთხვევაშიც."
        ]
    },
    ru: {
        currency: "₽",
        rulesBtn: "📖 Rules",
        history: "HISTORY:",
        noHistory: "No rounds yet",
        balance: "БАЛАНС",
        checkpoint: "СОХРАНЕНО",
        mult: "МНОЖИТЕЛЬ",
        win: "ВЫИГРЫШ",
        betLabel: "СТАВКА (₽)",
        minesLabel: "СЛОЖНОСТЬ",
        m1: "Легкий (Высокий шанс)",
        m2: "Средний (Баланс)",
        m3: "Сложный (Экстрим X)",
        startBtn: "СТАРТ (BET)",
        nextBtn: "ДАЛЕЕ ➡️",
        cashoutBtn: "ЗАБРАТЬ",
        readyMsg: "Сделайте ставку и начните",
        openingMsg: (w) => `${w}: Прыжок на 1-й блок...`,
        worldEnteredMsg: (w, nextWin, nextMult, curr) => `Вы в ${w}! Все 10 множителей видны. Нажмите ДАЛЕЕ для <strong style="color:#38bdf8;">${nextWin} ${curr}</strong> (${nextMult}x) или заберите!`,
        loseMsgZero: (amt, curr) => `Ядовитый гриб на 1-м блоке! ☠️ -${amt} ${curr}`,
        loseMsgGuaranteed: (amt, curr) => `Ядовитый гриб! ☠️ Но ваш СОХРАНЕННЫЙ ВЫИГРЫШ у вас: +${amt} ${curr}! 🛡️`,
        winMsg: (curWin, curMult, nextWin, nextMult, curr) => `Забрать <strong style="color:#fbbf24;">${curWin} ${curr}</strong> (${curMult}x) или за <strong style="color:#38bdf8;">${nextWin} ${curr}</strong> (${nextMult}x)?`,
        flagRunMsg: "🎉 Все 10 блоков пройдены! Откройте сундук или заберите выигрыш!",
        chestPrompt: (mult) => `🎁 3 СУНДУКА: 1x [${mult}X], 1x [1X], 1x [☠️ ГРИБ]`,
        chestWon: (boost, amt, curr) => `🌟 БУМ! +${boost}X БОНУС! Выигрыш: <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestSafe: (amt, curr) => `👍 Без множителя (1X)! Сумма: <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestLostZero: (curr, amt) => `☠️ В сундуке ядовитый гриб! Потеряно ${amt} ${curr}`,
        chestLostGuaranteed: (curr, amt) => `☠️ Гриб! Но сохранен прошлый гарантированный куш: +${amt} ${curr}! 🛡️`,
        worldClearMsg: (w, win, curr) => `🏰 ${w} Пройден! Заберите <strong style="color:#fbbf24;">${win} ${curr}</strong> или в Новый Мир!`,
        cashedOutMsg: (amt, mult, curr) => `Забрано: +${amt} ${curr} (${mult}x) 💰`,
        allClearedMsg: "👑 Победа! Все миры пройдены! 🏆",
        invalidBet: "Неверная ставка!",
        warpBtn: (nextW, curr, win) => `Перейти в Мир ${nextW} 🚀`,
        modalTitle: "Super Mario Worlds - Правила",
        modalRtp: "Теоретический RTP: 97.00% | Преимущество: 3.00%",
        modalRules: [
            "<strong>Легкий режим:</strong> Низкий риск грибов, множители до 2,800x.",
            "<strong>Средний режим:</strong> Сбалансированный риск и куш до 75,000x.",
            "<strong>Сложный режим:</strong> Высокий риск на каждом шаге, но множители до 12,000,000x!",
            "<strong>Реальный риск с 1-го блока:</strong> Шанс проигрыша активен сразу на первом шаге.",
            "<strong>Фиксированный Чекпоинт:</strong> Завершение Мира 1 сохраняет базовый куш даже при проигрыше в Мире 2."
        ]
    },
    es: {
        currency: "€",
        rulesBtn: "📖 Reglas",
        history: "HISTORIAL:",
        noHistory: "Sin rondas",
        balance: "SALDO",
        checkpoint: "GUARDADO",
        mult: "MULT",
        win: "GANANCIA",
        betLabel: "APUESTA (€)",
        minesLabel: "DIFICULTAD",
        m1: "Fácil (Alta tasa)",
        m2: "Medio (Equilibrado)",
        m3: "Difícil (Extremo X)",
        startBtn: "JUGAR (BET)",
        nextBtn: "SIGUIENTE ➡️",
        cashoutBtn: "RETIRAR",
        readyMsg: "Haz tu apuesta y juega",
        openingMsg: (w) => `${w}: Mario salta al 1er bloque...`,
        worldEnteredMsg: (w, nextWin, nextMult, curr) => `¡En ${w}! Los 10 multiplicadores listos. Pulsa SIGUIENTE por <strong style="color:#38bdf8;">${nextWin} ${curr}</strong> (${nextMult}x) o retira!`,
        loseMsgZero: (amt, curr) => `¡Champiñón Venenoso! ☠️ -${amt} ${curr}`,
        loseMsgGuaranteed: (amt, curr) => `¡Veneno! ☠️ Conservas tu GANANCIA GUARDADA: +${amt} ${curr}! 🛡️`,
        winMsg: (curWin, curMult, nextWin, nextMult, curr) => `¿Retirar <strong style="color:#fbbf24;">${curWin} ${curr}</strong> (${curMult}x) o <strong style="color:#38bdf8;">${nextWin} ${curr}</strong> (${nextMult}x)?`,
        flagRunMsg: "🎉 ¡10 Bloques Listos! ¡Elige cofre o retira!",
        chestPrompt: (mult) => `🎁 3 COFRES: 1x [${mult}X], 1x [1X], 1x [☠️ VENENO]`,
        chestWon: (boost, amt, curr) => `🌟 ¡BOOM! +${boost}X! Ganancia actual: <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestSafe: (amt, curr) => `👍 Pase Seguro (1X): <strong style="color:#fbbf24;">${amt} ${curr}</strong>!`,
        chestLostZero: (curr, amt) => `☠️ ¡Veneno en el cofre! Perdiste ${amt} ${curr}`,
        chestLostGuaranteed: (curr, amt) => `☠️ ¡Veneno! Conservas tu base guardada: +${amt} ${curr}! 🛡️`,
        worldClearMsg: (w, win, curr) => `🏰 ¡${w} Listo! Retira <strong style="color:#fbbf24;">${win} ${curr}</strong> o avanza!`,
        cashedOutMsg: (amt, mult, curr) => `Retirado: +${amt} ${curr} (${mult}x) 💰`,
        allClearedMsg: "👑 ¡Victoria Legendaria! 🏆",
        invalidBet: "¡Apuesta inválida!",
        warpBtn: (nextW, curr, win) => `Ir al Mundo ${nextW} 🚀`,
        modalTitle: "Super Mario Worlds - Reglas",
        modalRtp: "RTP Teórico: 97.00% | Ventaja: 3.00%",
        modalRules: [
            "<strong>Modo Fácil:</strong> Menor riesgo, multiplicadores hasta 2,800x.",
            "<strong>Modo Medio:</strong> Riesgo equilibrado con premios hasta 75,000x.",
            "<strong>Modo Difícil:</strong> Alto riesgo en cada paso, ¡con premios extremos hasta 12,000,000x!",
            "<strong>Riesgo real en el bloque 1:</strong> El veneno puede salir desde el primer paso.",
            "<strong>Checkpoint Guardado:</strong> Completar el Mundo 1 asegura la ganancia base."
        ]
    }
};

let currentLang = 'en';

class RetroAudio {
    constructor() { this.ctx = null; this.enabled = true; }
    init() { if (!this.ctx) this.ctx = new (window.AudioContext || window.webkitAudioContext)(); }
    playTone(freq, type, duration, startVol = 0.2, endVol = 0) {
        if (!this.enabled) return;
        this.init();
        try {
            const osc = this.ctx.createOscillator();
            const gain = this.ctx.createGain();
            osc.type = type;
            osc.frequency.setValueAtTime(freq, this.ctx.currentTime);
            gain.gain.setValueAtTime(startVol, this.ctx.currentTime);
            gain.gain.exponentialRampToValueAtTime(Math.max(endVol, 0.0001), this.ctx.currentTime + duration);
            osc.connect(gain);
            gain.connect(this.ctx.destination);
            osc.start();
            osc.stop(this.ctx.currentTime + duration);
        } catch(e) {}
    }
    jump() {
        if (!this.enabled) return;
        this.init();
        try {
            const osc = this.ctx.createOscillator();
            const gain = this.ctx.createGain();
            osc.type = 'square';
            osc.frequency.setValueAtTime(150, this.ctx.currentTime);
            osc.frequency.exponentialRampToValueAtTime(600, this.ctx.currentTime + 0.14);
            gain.gain.setValueAtTime(0.15, this.ctx.currentTime);
            gain.gain.linearRampToValueAtTime(0, this.ctx.currentTime + 0.14);
            osc.connect(gain);
            gain.connect(this.ctx.destination);
            osc.start();
            osc.stop(this.ctx.currentTime + 0.14);
        } catch(e) {}
    }
    coin() {
        if (!this.enabled) return;
        this.init();
        try {
            const now = this.ctx.currentTime;
            const osc = this.ctx.createOscillator();
            const gain = this.ctx.createGain();
            osc.type = 'sine';
            osc.frequency.setValueAtTime(987.77, now);
            osc.frequency.setValueAtTime(1318.51, now + 0.08);
            gain.gain.setValueAtTime(0.2, now);
            gain.gain.linearRampToValueAtTime(0, now + 0.35);
            osc.connect(gain);
            gain.connect(this.ctx.destination);
            osc.start();
            osc.stop(now + 0.35);
        } catch(e) {}
    }
    flag() {
        if (!this.enabled) return;
        const notes = [330, 392, 659, 523, 587, 784];
        notes.forEach((freq, idx) => {
            setTimeout(() => this.playTone(freq, 'triangle', 0.2, 0.25), idx * 100);
        });
    }
    chestOpen() {
        if (!this.enabled) return;
        const notes = [440, 554, 659, 880];
        notes.forEach((freq, idx) => {
            setTimeout(() => this.playTone(freq, 'sine', 0.15, 0.3), idx * 70);
        });
    }
    win() {
        if (!this.enabled) return;
        const notes = [523.25, 659.25, 783.99, 1046.50, 1318.51];
        notes.forEach((freq, idx) => {
            setTimeout(() => this.playTone(freq, 'triangle', 0.18, 0.25), idx * 75);
        });
    }
    lose() {
        if (!this.enabled) return;
        const notes = [400, 350, 300, 200];
        notes.forEach((freq, idx) => {
            setTimeout(() => this.playTone(freq, 'sawtooth', 0.18, 0.2), idx * 90);
        });
    }
}

const audio = new RetroAudio();

const canvas = document.getElementById('gameCanvas');
const ctx = canvas.getContext('2d');
const cabinet = document.getElementById('cabinet');

const balanceDisplay = document.getElementById('balance-display');
const checkpointDisplay = document.getElementById('checkpoint-display');
const multDisplay = document.getElementById('mult-display');
const winDisplay = document.getElementById('win-display');
const worldBadge = document.getElementById('world-badge');
const betInput = document.getElementById('bet-input');
const minesSelect = document.getElementById('mines-select');
const betBtn = document.getElementById('bet-btn');
const nextBtn = document.getElementById('next-btn');
const warpBtn = document.getElementById('warp-btn');
const cashoutBtn = document.getElementById('cashout-btn');
const statusMsg = document.getElementById('status-msg');
const historyBar = document.getElementById('history-bar');
const historyEmpty = document.getElementById('history-empty');

const bonusOverlay = document.getElementById('bonus-overlay');
const bonusTitle = document.getElementById('bonus-title');
const btnBonusCashout = document.getElementById('btn-bonus-cashout');

const langSelect = document.getElementById('lang-select');
const turboBtn = document.getElementById('turbo-btn');
const soundBtn = document.getElementById('sound-btn');
const rulesBtn = document.getElementById('rules-btn');
const closeModal = document.getElementById('close-modal');
const rulesModal = document.getElementById('rules-modal');
const modalTitle = document.getElementById('modal-title');
const modalBody = document.getElementById('modal-body');

const btnHalf = document.getElementById('btn-half');
const btnDouble = document.getElementById('btn-double');
const btnMax = document.getElementById('btn-max');

const lblHistory = document.getElementById('lbl-history');
const lblBalance = document.getElementById('lbl-balance');
const lblCheckpoint = document.getElementById('lbl-checkpoint');
const lblMult = document.getElementById('lbl-mult');
const lblWin = document.getElementById('lbl-win');
const lblBet = document.getElementById('lbl-bet');
const lblMines = document.getElementById('lbl-mines');
const optM1 = document.getElementById('opt-m1');
const optM2 = document.getElementById('opt-m2');
const optM3 = document.getElementById('opt-m3');

let isTurbo = false;
let particles = [];
let cameraX = 0;

let currentWorld = 1;
const BLOCKS_PER_WORLD = 10;
let accumulatedMult = 1.0;
let baseGuaranteedMult = 0.0;
let currentWorldBaseMult = 0.0;

const worldThemes = {
    1: { 
        name: "WORLD 1-1", 
        bg: ['#0284c7', '#38bdf8', '#7dd3fc', '#047857'], 
        ground: '#15803d', 
        subGround: '#78350f', 
        blockColor: '#f59e0b',
        blockBorder: '#b45309',
        chestBonus: 2 
    },
    2: { 
        name: "WORLD 1-2 (CAVE)", 
        bg: ['#1e1b4b', '#312e81', '#1e293b', '#0f172a'], 
        ground: '#475569', 
        subGround: '#1e293b', 
        blockColor: '#8b5cf6',
        blockBorder: '#6d28d9',
        chestBonus: 3 
    },
    3: { 
        name: "WORLD 1-3 (CASTLE)", 
        bg: ['#450a0a', '#7f1d1d', '#991b1b', '#09090b'], 
        ground: '#991b1b', 
        subGround: '#1c1917', 
        blockColor: '#ef4444',
        blockBorder: '#991b1b',
        chestBonus: 5 
    }
};

let chestContents = [];

const sprites = {
    mario: new Image(),
    marioJump: new Image(),
    poisonMushroom: new Image(),
    coin: new Image()
};

sprites.mario.src = "data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 40 56'><ellipse cx='20' cy='12' rx='14' ry='10' fill='%23ef4444'/><ellipse cx='28' cy='12' rx='6' ry='3' fill='%23ef4444'/><ellipse cx='20' cy='22' rx='11' ry='9' fill='%23fed7aa'/><circle cx='25' cy='19' r='2.5' fill='%23000'/><ellipse cx='26' cy='25' rx='7' ry='4' fill='%23451a03'/><ellipse cx='20' cy='38' rx='12' ry='12' fill='%232563eb'/><rect x='10' y='32' width='20' height='16' fill='%232563eb'/><circle cx='14' cy='34' r='2' fill='%23fbbf24'/><circle cx='26' cy='34' r='2' fill='%23fbbf24'/><rect x='6' y='30' width='6' height='10' fill='%23ef4444'/><rect x='28' y='30' width='6' height='10' fill='%23ef4444'/><circle cx='7' cy='42' r='4' fill='%23fff'/><circle cx='33' cy='42' r='4' fill='%23fff'/><ellipse cx='13' cy='52' rx='7' ry='4' fill='%2378350f'/><ellipse cx='27' cy='52' rx='7' ry='4' fill='%2378350f'/></svg>";
sprites.marioJump.src = "data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 40 56'><ellipse cx='20' cy='10' rx='14' ry='10' fill='%23ef4444'/><ellipse cx='28' cy='10' rx='6' ry='3' fill='%23ef4444'/><ellipse cx='20' cy='20' rx='11' ry='9' fill='%23fed7aa'/><circle cx='25' cy='17' r='2.5' fill='%23000'/><ellipse cx='26' cy='23' rx='7' ry='4' fill='%23451a03'/><ellipse cx='20' cy='36' rx='12' ry='11' fill='%232563eb'/><rect x='10' y='30' width='20' height='14' fill='%232563eb'/><circle cx='14' cy='32' r='2' fill='%23fbbf24'/><circle cx='26' cy='32' r='2' fill='%23fbbf24'/><rect x='4' y='20' width='8' height='12' fill='%23ef4444'/><circle cx='6' cy='18' r='4.5' fill='%23fff'/><ellipse cx='10' cy='48' rx='7' ry='5' fill='%2378350f'/><ellipse cx='30' cy='46' rx='7' ry='5' fill='%2378350f'/></svg>";
sprites.poisonMushroom.src = "data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 50 50'><path d='M5 28 C5 10, 45 10, 45 28 Z' fill='%239333ea'/><circle cx='16' cy='20' r='5' fill='%23e9d5ff'/><circle cx='34' cy='20' r='5' fill='%23e9d5ff'/><circle cx='25' cy='14' r='4' fill='%23e9d5ff'/><rect x='15' y='28' width='20' height='16' rx='4' fill='%23f3e8ff'/><ellipse cx='20' cy='34' rx='2' ry='4' fill='%23000'/><ellipse cx='30' cy='34' rx='2' ry='4' fill='%23000'/></svg>";
sprites.coin.src = "data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 40 40'><circle cx='20' cy='20' r='18' fill='%23fbbf24'/><circle cx='20' cy='20' r='14' fill='%23f59e0b'/><rect x='18' y='10' width='4' height='20' rx='2' fill='%23fff'/></svg>";

let balance = 1000;
let currentBet = 0;
let isPlaying = false;
let currentStep = 0;

const groundY = 230;
const mario = {
    x: 25,
    y: groundY - 54,
    w: 38,
    h: 54,
    targetX: 25,
    vy: 0,
    gravity: 0.95,
    state: 'idle'
};

let blocks = [];
let flagPole = { x: 0, y: 70, w: 10, h: 160, flagY: 80, isHit: false };

function formatMultiplierText(val) {
    if (val >= 1000000) return (val / 1000000).toFixed(val % 1000000 === 0 ? 0 : 1) + 'M';
    if (val >= 10000) return (val / 1000).toFixed(val % 1000 === 0 ? 0 : 1) + 'K';
    if (val >= 100) return Math.round(val) + 'x';
    return val.toFixed(2) + 'x';
}

function applyLanguage(lang) {
    currentLang = lang;
    const t = translations[lang];

    rulesBtn.textContent = t.rulesBtn;
    lblHistory.textContent = t.history;
    if (historyEmpty && historyBar.contains(historyEmpty)) historyEmpty.textContent = t.noHistory;

    lblBalance.textContent = t.balance;
    lblCheckpoint.textContent = t.checkpoint;
    lblMult.textContent = t.mult;
    lblWin.textContent = t.win;
    lblBet.textContent = t.betLabel;
    lblMines.textContent = t.minesLabel;

    optM1.textContent = t.m1;
    optM2.textContent = t.m2;
    optM3.textContent = t.m3;

    betBtn.textContent = t.startBtn;
    if (!isPlaying) {
        nextBtn.textContent = t.nextBtn;
        cashoutBtn.textContent = t.cashoutBtn;
        statusMsg.textContent = t.readyMsg;
    }

    modalTitle.textContent = t.modalTitle;
    modalBody.innerHTML = `
        <div class="rtp-box">
            <strong>${t.modalRtp}</strong>
        </div>
        <ul class="rule-list">
            ${t.modalRules.map(r => `<li>${r}</li>`).join('')}
        </ul>
    `;

    updateUI();
}

function spawnSparkles(x, y, color = '#fbbf24', count = 20) {
    for (let i = 0; i < count; i++) {
        const angle = Math.random() * Math.PI * 2;
        const speed = Math.random() * 5 + 2;
        particles.push({
            x: x, y: y,
            vx: Math.cos(angle) * speed,
            vy: Math.sin(angle) * speed - 2,
            size: Math.random() * 4.5 + 2,
            color: color, alpha: 1,
            decay: Math.random() * 0.03 + 0.02
        });
    }
}

function spawnConfetti() {
    const colors = ['#ef4444', '#3b82f6', '#fbbf24', '#22c55e', '#a855f7', '#ec4899'];
    for (let i = 0; i < 90; i++) {
        particles.push({
            x: cameraX + Math.random() * canvas.width,
            y: -10,
            vx: (Math.random() - 0.5) * 4,
            vy: Math.random() * 4 + 2,
            size: Math.random() * 6 + 3,
            color: colors[Math.floor(Math.random() * colors.length)],
            alpha: 1, decay: 0.007
        });
    }
}

function addHistory(mult, isWin) {
    if (historyEmpty && historyEmpty.parentNode) historyEmpty.remove();
    const badge = document.createElement('span');
    badge.className = `history-badge ${isWin ? 'badge-win' : 'badge-loss'}`;
    badge.textContent = `${isWin ? '+' : ''}${formatMultiplierText(mult)}`;
    historyBar.insertBefore(badge, historyBar.children[1]);
    if (historyBar.children.length > 8) historyBar.removeChild(historyBar.lastChild);
}

function initWorld(worldIndex) {
    blocks = [];
    currentWorld = worldIndex;
    worldBadge.textContent = worldThemes[currentWorld].name;
    
    const diffKey = parseInt(minesSelect.value || 2);
    const startX = 100;
    const spacing = 78;
    const curve = casinoMultiplierCurves[diffKey][currentWorld];

    for (let i = 0; i < BLOCKS_PER_WORLD; i++) {
        const mult = curve[i];
        blocks.push({
            x: startX + i * spacing,
            y: 85,
            w: 46,
            h: 46,
            mult: mult,
            hit: false,
            isPoison: false,
            bounce: 0
        });
    }

    flagPole.x = startX + BLOCKS_PER_WORLD * spacing + 40;
    flagPole.flagY = 80;
    flagPole.isHit = false;
}

function startGame() {
    const t = translations[currentLang];
    const bet = parseFloat(betInput.value);
    if (isNaN(bet) || bet <= 0 || bet > balance) {
        statusMsg.style.color = '#ef4444';
        statusMsg.textContent = t.invalidBet;
        return;
    }

    balance -= bet;
    currentBet = bet;
    isPlaying = true;
    currentStep = 0;
    accumulatedMult = 1.0;
    baseGuaranteedMult = 0.0;
    currentWorldBaseMult = 0.0;
    particles = [];
    bonusOverlay.style.display = 'none';

    initWorld(1);

    mario.x = 25;
    mario.y = groundY - mario.h;
    mario.targetX = 25;
    mario.vy = 0;
    cameraX = 0;

    updateUI();
    toggleControls(false);

    statusMsg.style.color = '#38bdf8';
    statusMsg.textContent = t.openingMsg(worldThemes[1].name);

    takeStep();
}

function takeStep() {
    if (!isPlaying) return;

    nextBtn.disabled = true;
    cashoutBtn.disabled = true;
    warpBtn.style.display = 'none';
    nextBtn.style.display = 'flex';

    if (currentStep < BLOCKS_PER_WORLD) {
        mario.targetX = blocks[currentStep].x + (blocks[currentStep].w - mario.w) / 2;
        mario.state = 'moving';
    }
}

function hitBlock() {
    const t = translations[currentLang];
    const block = blocks[currentStep];
    block.hit = true;
    block.bounce = 14;

    const diffKey = parseInt(minesSelect.value || 2);
    const curve = casinoMultiplierCurves[diffKey][currentWorld];
    const curM = curve[currentStep];
    const prevM = (currentStep === 0) ? (currentWorld === 1 ? 1.0 : casinoMultiplierCurves[diffKey][currentWorld - 1][BLOCKS_PER_WORLD - 1]) : curve[currentStep - 1];

    const survivalProb = Math.min(0.98, Math.max(0.01, (prevM / curM) * 0.97));
    const isPoison = (Math.random() > survivalProb);
    block.isPoison = isPoison;

    if (isPoison) {
        isPlaying = false;
        audio.lose();
        cabinet.classList.add('shake');
        setTimeout(() => cabinet.classList.remove('shake'), 400);

        spawnSparkles(block.x + block.w / 2, block.y, '#9333ea', 24);

        if (baseGuaranteedMult > 0) {
            const savedWin = currentBet * baseGuaranteedMult;
            balance += savedWin;
            addHistory(baseGuaranteedMult, true);
            statusMsg.style.color = '#c084fc';
            statusMsg.textContent = t.loseMsgGuaranteed(savedWin.toFixed(2), t.currency);
        } else {
            addHistory(0, false);
            statusMsg.style.color = '#ef4444';
            statusMsg.textContent = t.loseMsgZero(currentBet.toFixed(2), t.currency);
        }
        
        toggleControls(true);
        nextBtn.disabled = true;
        cashoutBtn.disabled = true;
        warpBtn.style.display = 'none';
        nextBtn.textContent = t.nextBtn;
        cashoutBtn.textContent = t.cashoutBtn;
        updateUI();
    } else {
        audio.coin();
        const currentMult = block.mult;
        const currentWinAmount = currentBet * currentMult;
        
        multDisplay.textContent = formatMultiplierText(currentMult);
        winDisplay.textContent = `${t.currency}${currentWinAmount.toFixed(2)}`;
        spawnSparkles(block.x + block.w / 2, block.y - 10, '#fbbf24', 20);

        currentStep++;

        if (currentStep >= BLOCKS_PER_WORLD) {
            reachFlag();
        } else {
            const nextMult = blocks[currentStep].mult;
            const nextWinAmount = currentBet * nextMult;

            cashoutBtn.textContent = `${t.cashoutBtn} (${t.currency}${currentWinAmount.toFixed(2)})`;
            nextBtn.textContent = `${t.nextBtn} (${t.currency}${nextWinAmount.toFixed(2)})`;

            statusMsg.style.color = '#4ade80';
            statusMsg.innerHTML = t.winMsg(currentWinAmount.toFixed(2), formatMultiplierText(currentMult), nextWinAmount.toFixed(2), formatMultiplierText(nextMult), t.currency);
            
            nextBtn.disabled = false;
            cashoutBtn.disabled = false;
        }
    }
}

function reachFlag() {
    const t = translations[currentLang];
    statusMsg.style.color = '#fbbf24';
    statusMsg.textContent = t.flagRunMsg;
    nextBtn.disabled = true;
    cashoutBtn.disabled = true;

    mario.targetX = flagPole.x - 25;
    mario.state = 'moving_to_flag';
}

function onFlagReached() {
    audio.flag();
    spawnConfetti();
    flagPole.isHit = true;
    
    currentWorldBaseMult = blocks[BLOCKS_PER_WORLD - 1].mult;
    accumulatedMult = currentWorldBaseMult;

    if (currentWorld === 1) {
        baseGuaranteedMult = currentWorldBaseMult;
    }

    updateUI();
    showBonusChests();
}

function showBonusChests() {
    const t = translations[currentLang];
    const bonusMultiplier = worldThemes[currentWorld].chestBonus;
    bonusTitle.textContent = t.chestPrompt(bonusMultiplier);
    
    chestContents = [bonusMultiplier, 1.0, 0];
    for (let i = chestContents.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [chestContents[i], chestContents[j]] = [chestContents[j], chestContents[i]];
    }

    const currentWinAmount = currentBet * accumulatedMult;
    btnBonusCashout.textContent = `${t.cashoutBtn} (${t.currency}${currentWinAmount.toFixed(2)})`;

    for (let i = 0; i < 3; i++) {
        const card = document.querySelectorAll('.chest-card')[i];
        const icon = card.querySelector('.chest-icon');
        const mult = card.querySelector('.chest-multiplier');
        icon.style.display = 'block';
        icon.textContent = '📦';
        mult.style.display = 'none';
        card.style.pointerEvents = 'auto';
        card.style.borderColor = '#eab308';
    }

    bonusOverlay.style.display = 'flex';
}

function openMysteryChest(index) {
    const t = translations[currentLang];
    audio.chestOpen();
    const result = chestContents[index];
    const cards = document.querySelectorAll('.chest-card');

    cards.forEach((c, idx) => {
        c.style.pointerEvents = 'none';
        const icon = c.querySelector('.chest-icon');
        const mult = c.querySelector('.chest-multiplier');
        icon.style.display = 'none';
        mult.style.display = 'block';

        const val = chestContents[idx];
        if (val === 0) {
            mult.textContent = '☠️ LOSE';
            mult.style.color = '#ef4444';
            c.style.borderColor = '#ef4444';
        } else if (val > 1.0) {
            mult.textContent = `🌟 ${val}X`;
            mult.style.color = '#fbbf24';
            c.style.borderColor = '#fbbf24';
        } else {
            mult.textContent = '1X SAFE';
            mult.style.color = '#94a3b8';
            c.style.borderColor = '#475569';
        }
    });

    if (result === 0) {
        isPlaying = false;
        audio.lose();
        cabinet.classList.add('shake');
        setTimeout(() => cabinet.classList.remove('shake'), 400);

        setTimeout(() => {
            bonusOverlay.style.display = 'none';
            if (baseGuaranteedMult > 0) {
                const savedWin = currentBet * baseGuaranteedMult;
                balance += savedWin;
                addHistory(baseGuaranteedMult, true);
                statusMsg.style.color = '#c084fc';
                statusMsg.textContent = t.chestLostGuaranteed(t.currency, savedWin.toFixed(2));
            } else {
                addHistory(0, false);
                statusMsg.style.color = '#ef4444';
                statusMsg.textContent = t.chestLostZero(t.currency, currentBet.toFixed(2));
            }
            toggleControls(true);
            nextBtn.disabled = true;
            cashoutBtn.disabled = true;
            warpBtn.style.display = 'none';
            nextBtn.textContent = t.nextBtn;
            cashoutBtn.textContent = t.cashoutBtn;
            updateUI();
        }, 1500);
        return;
    }

    baseGuaranteedMult = currentWorldBaseMult;
    accumulatedMult = parseFloat((accumulatedMult * result).toFixed(2));

    const currentWinAmount = currentBet * accumulatedMult;
    multDisplay.textContent = formatMultiplierText(accumulatedMult);
    winDisplay.textContent = `${t.currency}${currentWinAmount.toFixed(2)}`;
    checkpointDisplay.textContent = `${t.currency}${(currentBet * baseGuaranteedMult).toFixed(2)}`;

    if (result > 1.0) {
        audio.win();
        spawnSparkles(canvas.width / 2, canvas.height / 2, '#fbbf24', 35);
    }

    setTimeout(() => {
        bonusOverlay.style.display = 'none';

        if (result > 1.0) {
            statusMsg.innerHTML = t.chestWon(result, currentWinAmount.toFixed(2), t.currency);
        } else {
            statusMsg.innerHTML = t.chestSafe(currentWinAmount.toFixed(2), t.currency);
        }

        cashoutBtn.textContent = `${t.cashoutBtn} (${t.currency}${currentWinAmount.toFixed(2)})`;

        if (currentWorld < 3) {
            warpBtn.textContent = t.warpBtn(currentWorld + 1, t.currency, currentWinAmount.toFixed(2));
            nextBtn.style.display = 'none';
            warpBtn.style.display = 'flex';
            warpBtn.disabled = false;
            cashoutBtn.disabled = false;
        } else {
            cashOut();
            statusMsg.textContent = t.allClearedMsg;
        }
    }, 1500);
}

function cashOutFromBonus() {
    bonusOverlay.style.display = 'none';
    cashOut();
}

function warpToNextWorld() {
    if (!isPlaying) return;
    const t = translations[currentLang];
    currentWorld++;
    currentStep = 0;
    
    initWorld(currentWorld);

    mario.x = 25;
    mario.y = groundY - mario.h;
    mario.targetX = 25;
    mario.state = 'idle';
    cameraX = 0;

    warpBtn.style.display = 'none';
    nextBtn.style.display = 'flex';
    nextBtn.disabled = false;
    cashoutBtn.disabled = false;

    const currentWinAmount = currentBet * accumulatedMult;
    const nextMult = blocks[0].mult;
    const nextWinAmount = currentBet * nextMult;

    cashoutBtn.textContent = `${t.cashoutBtn} (${t.currency}${currentWinAmount.toFixed(2)})`;
    nextBtn.textContent = `${t.nextBtn} (${t.currency}${nextWinAmount.toFixed(2)})`;

    statusMsg.style.color = '#38bdf8';
    statusMsg.innerHTML = t.worldEnteredMsg(worldThemes[currentWorld].name, nextWinAmount.toFixed(2), formatMultiplierText(nextMult), t.currency);
}

function cashOut() {
    if (!isPlaying || currentStep === 0) return;
    const t = translations[currentLang];
    const finalMult = (flagPole.isHit) ? accumulatedMult : blocks[currentStep - 1].mult;
    const winAmount = currentBet * finalMult;
    balance += winAmount;
    isPlaying = false;

    audio.win();
    spawnConfetti();
    addHistory(finalMult, true);

    statusMsg.style.color = '#fbbf24';
    statusMsg.textContent = t.cashedOutMsg(winAmount.toFixed(2), formatMultiplierText(finalMult), t.currency);

    toggleControls(true);
    nextBtn.disabled = true;
    cashoutBtn.disabled = true;
    warpBtn.style.display = 'none';
    nextBtn.style.display = 'flex';
    nextBtn.textContent = t.nextBtn;
    cashoutBtn.textContent = t.cashoutBtn;
    baseGuaranteedMult = 0.0;
    currentWorldBaseMult = 0.0;
    updateUI();
}

function toggleControls(enable) {
    betBtn.disabled = !enable;
    betInput.disabled = !enable;
    minesSelect.disabled = !enable;
    btnHalf.disabled = !enable;
    btnDouble.disabled = !enable;
    btnMax.disabled = !enable;
    langSelect.disabled = !enable;
}

function updateUI() {
    const t = translations[currentLang];
    balanceDisplay.textContent = `${t.currency}${balance.toFixed(2)}`;
    checkpointDisplay.textContent = `${t.currency}${(currentBet * baseGuaranteedMult).toFixed(2)}`;
    if (!isPlaying) {
        multDisplay.textContent = '1.00x';
        winDisplay.textContent = `${t.currency}0.00`;
        checkpointDisplay.textContent = `${t.currency}0.00`;
        worldBadge.textContent = "WORLD 1-1";
    }
}

function update() {
    const speed = isTurbo ? 14 : 7;

    if (mario.state === 'moving') {
        const dx = mario.targetX - mario.x;
        if (Math.abs(dx) > speed) {
            mario.x += Math.sign(dx) * speed;
        } else {
            mario.x = mario.targetX;
            mario.state = 'jumping';
            mario.vy = isTurbo ? -15 : -12.5;
            audio.jump();
        }
    } else if (mario.state === 'moving_to_flag') {
        const dx = mario.targetX - mario.x;
        if (Math.abs(dx) > speed) {
            mario.x += Math.sign(dx) * speed;
        } else {
            mario.x = mario.targetX;
            mario.state = 'idle';
            onFlagReached();
        }
    }

    if (mario.state === 'jumping') {
        mario.y += mario.vy;
        mario.vy += mario.gravity * (isTurbo ? 1.6 : 1);

        const currentBlock = blocks[currentStep];
        if (mario.vy < 0 && mario.y <= currentBlock.y + currentBlock.h) {
            mario.y = currentBlock.y + currentBlock.h;
            mario.vy = 3;
            hitBlock();
        }

        if (mario.y >= groundY - mario.h) {
            mario.y = groundY - mario.h;
            mario.vy = 0;
            if (mario.state === 'jumping') mario.state = 'idle';
        }
    }

    const targetCameraX = Math.max(0, mario.x - 180);
    cameraX += (targetCameraX - cameraX) * 0.1;

    if (flagPole.isHit && flagPole.flagY < groundY - 40) {
        flagPole.flagY += 3;
    }

    blocks.forEach(b => {
        if (b.bounce > 0) b.bounce -= (isTurbo ? 3 : 1.5);
    });

    for (let i = particles.length - 1; i >= 0; i--) {
        const p = particles[i];
        p.x += p.vx;
        p.y += p.vy;
        p.alpha -= p.decay;
        if (p.alpha <= 0) particles.splice(i, 1);
    }
}

function draw() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);

    const theme = worldThemes[currentWorld];

    // Background Gradient
    const bgGrad = ctx.createLinearGradient(0, 0, 0, canvas.height);
    bgGrad.addColorStop(0, theme.bg[0]);
    bgGrad.addColorStop(0.5, theme.bg[1]);
    bgGrad.addColorStop(0.8, theme.bg[2]);
    bgGrad.addColorStop(1, theme.bg[3]);
    ctx.fillStyle = bgGrad;
    ctx.fillRect(0, 0, canvas.width, canvas.height);

    ctx.save();
    ctx.translate(-cameraX, 0);

    // Parallax Environmental Details
    if (currentWorld === 1) {
        ctx.fillStyle = "rgba(251, 191, 36, 0.15)";
        ctx.beginPath();
        ctx.arc(200, 30, 90, 0, Math.PI * 2);
        ctx.fill();

        ctx.fillStyle = "rgba(255, 255, 255, 0.85)";
        for (let x = 80; x < 1300; x += 280) {
            ctx.beginPath();
            ctx.arc(x, 42, 16, 0, Math.PI * 2);
            ctx.arc(x + 20, 34, 24, 0, Math.PI * 2);
            ctx.arc(x + 42, 42, 16, 0, Math.PI * 2);
            ctx.fill();
        }

        ctx.fillStyle = "#16a34a";
        for (let h = 40; h < 1300; h += 320) {
            ctx.beginPath();
            ctx.arc(h, 230, 75, Math.PI, 0);
            ctx.fill();
        }
    } else if (currentWorld === 2) {
        ctx.fillStyle = "rgba(139, 92, 246, 0.2)";
        for (let cx = 120; cx < 1200; cx += 220) {
            ctx.beginPath();
            ctx.arc(cx, 60, 45, 0, Math.PI * 2);
            ctx.fill();
        }
    } else if (currentWorld === 3) {
        ctx.fillStyle = "rgba(239, 68, 68, 0.25)";
        for (let mx = 90; mx < 1200; mx += 180) {
            ctx.beginPath();
            ctx.arc(mx, 120, 50, 0, Math.PI * 2);
            ctx.fill();
        }
    }

    // Ground Rendering
    ctx.fillStyle = theme.ground;
    ctx.fillRect(0, groundY, 1400, 8);
    ctx.fillStyle = "rgba(0,0,0,0.2)";
    ctx.fillRect(0, groundY + 6, 1400, 2);

    ctx.fillStyle = theme.subGround;
    ctx.fillRect(0, groundY + 8, 1400, canvas.height - groundY - 8);

    // 3D Blocks Rendering with Floating Badges
    blocks.forEach((b) => {
        const renderY = b.y - b.bounce;

        if (!b.hit) {
            ctx.fillStyle = theme.blockBorder;
            ctx.beginPath();
            ctx.roundRect(b.x, renderY, b.w, b.h, 8);
            ctx.fill();

            ctx.fillStyle = theme.blockColor;
            ctx.beginPath();
            ctx.roundRect(b.x + 2, renderY + 2, b.w - 4, b.h - 4, 6);
            ctx.fill();

            ctx.fillStyle = "rgba(255, 255, 255, 0.35)";
            ctx.fillRect(b.x + 4, renderY + 4, b.w - 8, 3);

            ctx.fillStyle = "#fff";
            ctx.font = '900 20px "Fredoka", sans-serif';
            ctx.textAlign = 'center';
            ctx.fillText('?', b.x + b.w / 2, renderY + 30);

            if (b.mult > 0) {
                const multText = formatMultiplierText(b.mult);
                ctx.font = '800 10.5px "Outfit", sans-serif';
                const textWidth = ctx.measureText(multText).width;
                const badgeW = textWidth + 12;
                const badgeH = 18;
                const badgeX = b.x + (b.w - badgeW) / 2;
                const badgeY = renderY - 24;

                ctx.fillStyle = "rgba(15, 23, 42, 0.85)";
                ctx.strokeStyle = "rgba(255, 255, 255, 0.25)";
                ctx.lineWidth = 1;
                ctx.beginPath();
                ctx.roundRect(badgeX, badgeY, badgeW, badgeH, 6);
                ctx.fill();
                ctx.stroke();

                ctx.fillStyle = b.mult >= 50 ? '#fbbf24' : '#38bdf8';
                ctx.textAlign = 'center';
                ctx.fillText(multText, b.x + b.w / 2, badgeY + 13);
            }
        } else {
            ctx.fillStyle = '#334155';
            ctx.beginPath();
            ctx.roundRect(b.x, renderY, b.w, b.h, 8);
            ctx.fill();

            ctx.fillStyle = '#475569';
            ctx.beginPath();
            ctx.roundRect(b.x + 2, renderY + 2, b.w - 4, b.h - 4, 6);
            ctx.fill();

            if (b.isPoison) {
                ctx.drawImage(sprites.poisonMushroom, b.x + (b.w - 38) / 2, renderY - 40, 38, 38);
            } else {
                ctx.drawImage(sprites.coin, b.x + (b.w - 30) / 2, renderY - 36, 30, 30);
                
                ctx.fillStyle = '#22c55e';
                ctx.font = '900 12px "Outfit", sans-serif';
                ctx.textAlign = 'center';
                ctx.fillText(formatMultiplierText(b.mult), b.x + b.w / 2, renderY - 42);
            }
        }
    });

    // Flagpole
    ctx.fillStyle = '#cbd5e1';
    ctx.fillRect(flagPole.x, flagPole.y, flagPole.w, flagPole.h);
    ctx.fillStyle = '#fbbf24';
    ctx.beginPath();
    ctx.arc(flagPole.x + 5, flagPole.y, 9, 0, Math.PI * 2);
    ctx.fill();

    // Flag
    ctx.fillStyle = '#22c55e';
    ctx.beginPath();
    ctx.moveTo(flagPole.x + 10, flagPole.flagY);
    ctx.lineTo(flagPole.x + 40, flagPole.flagY + 14);
    ctx.lineTo(flagPole.x + 10, flagPole.flagY + 28);
    ctx.fill();

    // Castle
    ctx.fillStyle = '#334155';
    ctx.fillRect(flagPole.x + 65, groundY - 85, 85, 85);
    ctx.fillStyle = '#0f172a';
    ctx.fillRect(flagPole.x + 92, groundY - 45, 32, 45);

    // Particles
    particles.forEach(p => {
        ctx.save();
        ctx.globalAlpha = p.alpha;
        ctx.fillStyle = p.color;
        ctx.beginPath();
        ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
        ctx.fill();
        ctx.restore();
    });

    // Mario Shadow
    ctx.fillStyle = "rgba(0, 0, 0, 0.25)";
    ctx.beginPath();
    ctx.ellipse(mario.x + mario.w / 2, groundY, mario.w / 2, 5, 0, 0, Math.PI * 2);
    ctx.fill();

    // Mario Vector Character
    const currentMario = (mario.state === 'jumping') ? sprites.marioJump : sprites.mario;
    ctx.drawImage(currentMario, mario.x, mario.y, mario.w, mario.h);

    ctx.restore();
}

function gameLoop() {
    update();
    draw();
    requestAnimationFrame(gameLoop);
}

btnHalf.addEventListener('click', () => betInput.value = Math.max(1, Math.floor(parseFloat(betInput.value || 10) / 2)));
btnDouble.addEventListener('click', () => betInput.value = Math.min(balance, Math.floor(parseFloat(betInput.value || 10) * 2)));
btnMax.addEventListener('click', () => betInput.value = Math.floor(balance));

turboBtn.addEventListener('click', () => {
    isTurbo = !isTurbo;
    turboBtn.classList.toggle('active', isTurbo);
    turboBtn.textContent = `⚡ Turbo: ${isTurbo ? 'ON' : 'OFF'}`;
});

soundBtn.addEventListener('click', () => {
    audio.enabled = !audio.enabled;
    soundBtn.classList.toggle('active', audio.enabled);
    soundBtn.textContent = `🔊 Sound: ${audio.enabled ? 'ON' : 'OFF'}`;
});

langSelect.addEventListener('change', (e) => applyLanguage(e.target.value));

rulesBtn.addEventListener('click', () => rulesModal.style.display = 'flex');
closeModal.addEventListener('click', () => rulesModal.style.display = 'none');
window.addEventListener('click', (e) => { if (e.target === rulesModal) rulesModal.style.display = 'none'; });

betBtn.addEventListener('click', startGame);
nextBtn.addEventListener('click', takeStep);
warpBtn.addEventListener('click', warpToNextWorld);
cashoutBtn.addEventListener('click', cashOut);

minesSelect.addEventListener('change', () => {
    initWorld(currentWorld);
    if (!isPlaying) {
        statusMsg.textContent = translations[currentLang].readyMsg;
    }
});

applyLanguage('en');
initWorld(1);
gameLoop();
</script>
</body>
</html>
