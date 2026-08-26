<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2nd Grade Villa Girls Soccer Schedule & Practices | Villa Duchesne Theme</title>
    <!-- Google Fonts for typography inspired by Villa Duchesne -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-maroon: #6B1D2F;
            --dark-maroon: #4A121F;
            --accent-gold: #C5A059;
            --light-gold: #F4EBE1;
            --bg-cream: #FAF8F5;
            --text-dark: #2C2C2C;
            --text-muted: #666666;
            --white: #FFFFFF;
            --border-color: #E2D9CE;
            --shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s ease;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg-cream);
            color: var(--text-dark);
            line-height: 1.4;
            width: 100%;
            overflow-x: hidden;
        }

        /* Top Bar: Coach Contact Info */
        .coach-bar {
            background-color: var(--dark-maroon);
            color: var(--light-gold);
            padding: 6px 12px;
            font-size: clamp(0.72rem, 2.2vw, 0.82rem);
            border-bottom: 1px solid rgba(197, 160, 89, 0.3);
            width: 100%;
        }

        .coach-container {
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 2px;
            text-align: center;
        }

        .coach-head-row {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px 14px;
            flex-wrap: wrap;
        }

        .coach-assistant-row {
            color: var(--light-gold);
            font-size: clamp(0.68rem, 2vw, 0.78rem);
            opacity: 0.95;
        }

        .coach-title {
            font-weight: 700;
            color: var(--accent-gold);
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        .coach-name {
            color: var(--light-gold);
            font-weight: 400;
        }

        .coach-details {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        .coach-item {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            color: var(--light-gold);
            text-decoration: none;
            transition: var(--transition);
        }

        .coach-item:hover {
            color: var(--accent-gold);
            text-decoration: underline;
        }

        .coach-item svg {
            width: 12px;
            height: 12px;
            fill: var(--accent-gold);
            flex-shrink: 0;
        }

        /* Header / Hero Section */
        header {
            background: linear-gradient(135deg, rgba(74, 18, 31, 0.88) 0%, rgba(107, 29, 47, 0.82) 100%),
                        url('https://raw.githubusercontent.com/mattwootten/2nd-Grade-Girls-Soccer/3735de8155cb5040f6f877bb48b12043d6e4f09f/hero-banner.jpeg') center 35%/cover no-repeat;
            color: var(--white);
            text-align: center;
            padding: clamp(14px, 3.5vw, 24px) 12px;
            position: relative;
            border-bottom: 4px solid var(--accent-gold);
            width: 100%;
        }

        .header-content {
            max-width: 900px;
            margin: 0 auto;
        }

        .villa-logo {
            max-width: clamp(140px, 30vw, 210px);
            height: auto;
            margin-bottom: 6px;
            filter: drop-shadow(0 2px 4px rgba(0,0,0,0.3));
        }

        header h1 {
            font-family: 'Cormorant Garamond', serif;
            font-size: clamp(1.35rem, 3.8vw, 2.1rem);
            font-weight: 700;
            letter-spacing: 0.5px;
            margin-bottom: 2px;
            text-transform: uppercase;
            line-height: 1.15;
            font-variant-numeric: lining-nums;
        }

        header h1 .num-two {
            font-size: 1.2em;
            display: inline-block;
            vertical-align: baseline;
        }

        header h1 sup {
            font-size: 0.6em;
            top: -0.4em;
        }

        header p {
            font-size: clamp(0.72rem, 1.8vw, 0.9rem);
            color: var(--light-gold);
            letter-spacing: 1.2px;
            text-transform: uppercase;
            font-weight: 500;
            margin-top: 2px;
        }

        /* Tab Navigation Bar */
        .tab-nav {
            display: flex;
            justify-content: center;
            background: var(--dark-maroon);
            border-bottom: 2px solid var(--accent-gold);
            width: 100%;
        }

        .tab-btn {
            padding: 10px 16px;
            background: transparent;
            color: var(--light-gold);
            border: none;
            font-family: 'Montserrat', sans-serif;
            font-size: clamp(0.72rem, 2vw, 0.85rem);
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            cursor: pointer;
            transition: var(--transition);
            border-bottom: 3px solid transparent;
            flex: 1;
            max-width: 250px;
            text-align: center;
        }

        .tab-btn:hover {
            color: var(--white);
            background: rgba(255, 255, 255, 0.05);
        }

        .tab-btn.active {
            color: var(--accent-gold);
            border-bottom-color: var(--accent-gold);
            background: rgba(0, 0, 0, 0.2);
        }

        /* Main Container */
        .container {
            max-width: 1100px;
            margin: 12px auto 25px;
            padding: 0 12px;
            width: 100%;
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        /* Controls Bar with Instructions */
        .controls {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 15px;
            background: var(--white);
            padding: 10px 14px;
            border-radius: 8px;
            box-shadow: var(--shadow);
            border: 1px solid var(--border-color);
            width: 100%;
            flex-wrap: wrap;
        }

        .btn {
            background: transparent;
            border: 1.5px solid var(--primary-maroon);
            color: var(--primary-maroon);
            padding: 8px 12px;
            border-radius: 4px;
            font-weight: 600;
            font-size: 0.75rem;
            cursor: pointer;
            transition: var(--transition);
            text-transform: uppercase;
            letter-spacing: 0.3px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 6px;
            text-decoration: none;
            white-space: nowrap;
            flex-shrink: 0;
        }

        .btn:hover {
            background: var(--primary-maroon);
            color: var(--white);
        }

        .btn-gold {
            background: var(--accent-gold);
            border-color: var(--accent-gold);
            color: var(--dark-maroon);
        }

        .btn-gold:hover {
            background: #b08c45;
            border-color: #b08c45;
            color: var(--white);
        }

        .btn svg {
            width: 14px;
            height: 14px;
            fill: currentColor;
            flex-shrink: 0;
        }

        .ical-instruction {
            font-size: clamp(0.75rem, 2vw, 0.82rem);
            color: var(--text-muted);
            line-height: 1.3;
            flex: 1 1 200px;
        }

        /* Schedule Grid Layout */
        .schedule-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(min(100%, 310px), 1fr));
            gap: 15px;
            width: 100%;
        }

        .game-card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--shadow);
            border: 1px solid var(--border-color);
            transition: var(--transition);
            display: flex;
            flex-direction: column;
            width: 100%;
        }

        .game-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }

        .card-header {
            background-color: var(--primary-maroon);
            color: var(--white);
            padding: 10px 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 8px;
        }

        .date-badge {
            font-weight: 700;
            font-size: 0.85rem;
            letter-spacing: 0.3px;
        }

        .time-badge {
            background: var(--accent-gold);
            color: var(--dark-maroon);
            padding: 2px 6px;
            border-radius: 3px;
            font-size: 0.7rem;
            font-weight: 700;
            text-transform: uppercase;
            white-space: nowrap;
        }

        .card-body {
            padding: 14px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }

        .event-title {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.25rem;
            font-weight: 700;
            color: var(--primary-maroon);
            margin-bottom: 8px;
            line-height: 1.2;
        }

        .info-row {
            display: flex;
            align-items: flex-start;
            margin-bottom: 6px;
            font-size: 0.82rem;
        }

        .info-row svg {
            width: 14px;
            height: 14px;
            fill: var(--accent-gold);
            margin-right: 6px;
            flex-shrink: 0;
            margin-top: 2px;
        }

        .info-label {
            font-weight: 600;
            color: var(--text-dark);
            margin-right: 4px;
        }

        .info-value {
            color: var(--text-muted);
            word-break: break-word;
            overflow-wrap: anywhere;
        }

        /* Snack Section inside Cards */
        .snack-section {
            margin-top: auto;
            padding-top: 8px;
            border-top: 1px dashed var(--border-color);
        }

        .snack-form-group {
            display: flex;
            gap: 6px;
            margin-top: 6px;
        }

        .snack-input {
            flex: 1;
            padding: 5px 8px;
            border: 1px solid var(--border-color);
            border-radius: 4px;
            font-size: 0.78rem;
            font-family: inherit;
        }

        .snack-input:focus {
            border-color: var(--accent-gold);
            outline: none;
        }

        .snack-status-bar {
            background: var(--white);
            border-radius: 8px;
            box-shadow: var(--shadow);
            border: 1px solid var(--border-color);
            padding: 10px 12px;
            margin-bottom: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 6px;
        }

        .snack-status-text {
            font-size: 0.82rem;
            color: var(--text-muted);
        }

        .snack-sync-notice {
            font-size: 0.78rem;
            font-weight: 600;
            color: var(--primary-maroon);
        }

        .card-footer {
            border-top: 1px solid var(--border-color);
            padding: 8px 14px;
            background-color: #FAFAFA;
            display: flex;
            justify-content: flex-end;
        }

        .map-btn {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            color: var(--primary-maroon);
            text-decoration: none;
            font-size: 0.78rem;
            font-weight: 600;
            transition: var(--transition);
        }

        .map-btn:hover {
            color: var(--accent-gold);
        }

        .map-btn svg {
            width: 13px;
            height: 13px;
            fill: currentColor;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px 15px;
            background: var(--dark-maroon);
            color: var(--light-gold);
            margin-top: 30px;
            font-size: 0.78rem;
            border-top: 3px solid var(--accent-gold);
            width: 100%;
        }

        footer p {
            margin-bottom: 4px;
        }

        @media (max-width: 480px) {
            .btn {
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- Top Coach Contact Bar -->
    <div class="coach-bar">
        <div class="coach-container">
            <div class="coach-head-row">
                <div>
                    <span class="coach-title">Coach:</span>
                    <span class="coach-name">Matt Wootten</span>
                </div>
                <div class="coach-details">
                    <a href="tel:6362840190" class="coach-item">
                        <svg viewBox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
                        636-284-0190
                    </a>
                    <a href="mailto:matt.wootten@gmail.com" class="coach-item">
                        <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
                        matt.wootten@gmail.com
                    </a>
                </div>
            </div>
            <div class="coach-assistant-row">
                <span class="coach-title">Assistant Coaches:</span> Justin Lierz &amp; Eddie Ibarra
            </div>
        </div>
    </div>

    <!-- Hero Header -->
    <header>
        <div class="header-content">
            <img class="villa-logo" src="https://resources.finalsite.net/images/f_auto,q_auto/v1658736895/vdoh/s8isqiliyh9ktoymnanr/Logo_Horizontal.png" alt="Villa Duchesne Logo">
            <h1><span class="num-two">2</span><sup>nd</sup> Grade Villa Girls Soccer Schedule</h1>
            <p>Fall 2026 Athletics Season</p>
        </div>
    </header>

    <!-- Tab Navigation -->
    <div class="tab-nav">
        <button class="tab-btn active" onclick="switchTab('games', this)">Game Schedule</button>
        <button class="tab-btn" onclick="switchTab('practices', this)">Practice Schedule</button>
    </div>

    <div class="container">

        <!-- TAB 1: GAME SCHEDULE -->
        <div id="games" class="tab-content active">
            <!-- Controls Section -->
            <div class="controls">
                <button class="btn btn-gold" onclick="downloadICS()">
                    <svg viewBox="0 0 24 24"><path d="M19 4h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V10h14v10zm0-12H5V6h14v2zm-7 5h5v5h-5z"/></svg>
                    Download iCal (.ics)
                </button>
                <div class="ical-instruction">
                    Clicking this will download the full game schedule to automatically add all games directly into your Apple, Google, or Outlook calendar app.
                </div>
            </div>

            <!-- Schedule Cards Grid -->
            <div class="schedule-grid" id="gameGrid">
                <!-- Rendered by JavaScript -->
            </div>
        </div>

        <!-- TAB 2: PRACTICES -->
        <div id="practices" class="tab-content">
            <div class="snack-status-bar">
                <span class="snack-status-text">Practices are held Tuesdays from 3:00 - 4:15 PM CDT. Sign up for snacks below.</span>
                <span id="snackSyncNotice" class="snack-sync-notice"></span>
            </div>

            <div class="schedule-grid" id="practiceGrid">
                <!-- Rendered by JavaScript -->
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 2nd Grade Girls Soccer • Villa Duchesne</p>
        <p>Designed with faith, community, and excellence.</p>
    </footer>

    <script>
        // Games Dataset
        const gameData = [
            { id: "g1", title: "St. Francis of Assisi School (A)", date: "Sun, Aug 30, 2026", time: "2:00 PM CDT", label: "Field", loc: "Wehner - Odenwald, Field #1", addr: "7600 Hazel Ave, St. Louis, MO 63119", map: "https://maps.google.com/?q=7600+Hazel+Ave,+St.+Louis,+MO+63119" },
            { id: "g2", title: "Mary Queen of Peace School (A)", date: "Sat, Sep 12, 2026", time: "1:00 PM CDT", label: "Field", loc: "Bussen Park, Field 1B", addr: "400 Magoffin Rd, St. Louis, MO 63129", map: "https://maps.google.com/?q=400+Magoffin+Rd,+St.+Louis,+MO+63129" },
            { id: "g3", title: "St. Gabriel School (A)", date: "Sat, Sep 19, 2026", time: "2:00 PM CDT", label: "Location", loc: "St. Justin the Martyr School", addr: "11910 Eddie & Park Rd, St. Louis, MO 63126", map: "https://maps.google.com/?q=11910+Eddie+%26+Park+Rd,+St.+Louis,+MO+63126" },
            { id: "g4", title: "St. Margaret Mary Alacoque School (A)", date: "Sun, Sep 20, 2026", time: "1:00 PM CDT", label: "Location", loc: "St. Margaret Mary Alacoque School", addr: "4900 Ringer Rd, St. Louis, MO 63129", map: "https://maps.google.com/?q=4900+Ringer+Rd,+St.+Louis,+MO+63129" },
            { id: "g5", title: "Christ the King Catholic School (A)", date: "Sun, Sep 27, 2026", time: "1:00 PM CDT", label: "Location", loc: "Visitation Academy of St Louis", addr: "3020 N Ballas Rd, St. Louis, MO 63131", map: "https://maps.google.com/?q=3020+N+Ballas+Rd,+St.+Louis,+MO+63131" },
            { id: "g6", title: "Our Lady of the Pillar School (A)", date: "Sun, Oct 4, 2026", time: "1:00 PM CDT", label: "Location", loc: "Odenwald", addr: "7600 Hazel Ave, St. Louis, MO 63119", map: "https://maps.google.com/?q=7600+Hazel+Ave,+St.+Louis,+MO+63119" },
            { id: "g7", title: "Mary Queen of Peace School (A)", date: "Sat, Oct 17, 2026", time: "3:00 PM CDT", label: "Field", loc: "Kirkwood Park, Upper Field A", addr: "574 W Adams Ave, Kirkwood, MO 63122", map: "https://maps.google.com/?q=574+W+Adams+Ave,+Kirkwood,+MO+63122" },
            { id: "g8", title: "St. Gabriel School (A)", date: "Sun, Oct 25, 2026", time: "1:00 PM CDT", label: "Location", loc: "Holy Redeemer Catholic School", addr: "17 Joy Ave, Webster Groves, MO 63119", map: "https://maps.google.com/?q=17+Joy+Ave,+Webster+Groves,+MO+63119" }
        ];

        // Practice Dates Dataset
        const practiceData = [
            { id: "p1", date: "Tuesday, Aug 25, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p2", date: "Tuesday, Sep 1, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p3", date: "Tuesday, Sep 8, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p4", date: "Tuesday, Sep 15, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p5", date: "Tuesday, Sep 22, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p6", date: "Tuesday, Sep 29, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p7", date: "Tuesday, Oct 6, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p8", date: "Tuesday, Oct 13, 2026", time: "3:00 - 4:15 PM CDT" },
            { id: "p9", date: "Tuesday, Oct 20, 2026", time: "3:00 - 4:15 PM CDT" }
        ];

        // JSONBin.io Credentials
        const BIN_ID = "6a8dc61bf5f4af5e2940fbbf";
        const API_KEY = "$2a$10$3XT2O7GyzmJ6R0zKT4UB2OrLtJWkwivcmmrxkWYQNZzLKKn7EFTR2";
        const JSONBIN_URL = `https://api.jsonbin.io/v3/b/${BIN_ID}`;

        let snackData = {};

        function switchTab(tabId, btn) {
            document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
            btn.classList.add('active');
        }

        async function loadSnackData() {
            const local = localStorage.getItem("villa_soccer_snacks");
            if (local) {
                try { snackData = JSON.parse(local); } catch(e){}
            }

            try {
                const res = await fetch(`${JSONBIN_URL}/latest`, {
                    headers: {
                        "X-Master-Key": API_KEY
                    }
                });
                if (res.ok) {
                    const result = await res.json();
                    if (result.record) {
                        snackData = result.record;
                        localStorage.setItem("villa_soccer_snacks", JSON.stringify(snackData));
                    }
                }
            } catch (e) {
                console.log("Using local cache fallback.");
            }

            renderGames();
            renderPractices();
        }

        function renderGames() {
            const grid = document.getElementById('gameGrid');
            grid.innerHTML = '';

            gameData.forEach(item => {
                const signedUp = snackData[item.id] || "";
                const card = document.createElement('div');
                card.className = 'game-card';
                card.innerHTML = `
                    <div class="card-header">
                        <span class="date-badge">${item.date}</span>
                        <span class="time-badge">${item.time}</span>
                    </div>
                    <div class="card-body">
                        <div class="event-title">${item.title}</div>
                        <div class="info-row">
                            <svg viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
                            <div>
                                <span class="info-label">${item.label}:</span>
                                <span class="info-value">${item.loc}</span>
                            </div>
                        </div>
                        <div class="info-row">
                            <svg viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
                            <div>
                                <span class="info-label">Address:</span>
                                <span class="info-value">${item.addr}</span>
                            </div>
                        </div>

                        <div class="snack-section">
                            <div class="info-row">
                                <svg viewBox="0 0 24 24"><path d="M18 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zM9 4h2v5l-1-.75L9 9V4zm9 16H6V4h1v9l3-2.25L13 13V4h5v16z"/></svg>
                                <div>
                                    <span class="info-label">Snacks:</span>
                                    <span class="info-value">${signedUp ? `<strong>${signedUp}</strong>` : '<em>Not claimed</em>'}</span>
                                </div>
                            </div>
                            <div class="snack-form-group">
                                <input type="text" class="snack-input" id="input-${item.id}" placeholder="Enter name..." value="${signedUp}">
                                <button class="btn btn-gold" onclick="saveSnack('${item.id}')">Save</button>
                            </div>
                        </div>
                    </div>
                    <div class="card-footer">
                        <a href="${item.map}" target="_blank" class="map-btn">
                            Get Directions
                            <svg viewBox="0 0 24 24"><path d="M14 3h7v7h-2V6.41l-9.29 9.3-1.42-1.42 9.3-9.29H14V3zM5 5h6v2H5v12h12v-6h2v6c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2V7c0-1.1.9-2 2-2z"/></svg>
                        </a>
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        function renderPractices() {
            const grid = document.getElementById('practiceGrid');
            grid.innerHTML = '';

            practiceData.forEach(item => {
                const signedUp = snackData[item.id] || "";
                const card = document.createElement('div');
                card.className = 'game-card';
                card.innerHTML = `
                    <div class="card-header">
                        <span class="date-badge">${item.date}</span>
                        <span class="time-badge">${item.time}</span>
                    </div>
                    <div class="card-body">
                        <div class="event-title">Team Practice</div>
                        <div class="info-row">
                            <svg viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
                            <div>
                                <span class="info-label">Event:</span>
                                <span class="info-value">Weekly Soccer Practice</span>
                            </div>
                        </div>

                        <div class="snack-section">
                            <div class="info-row">
                                <svg viewBox="0 0 24 24"><path d="M18 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zM9 4h2v5l-1-.75L9 9V4zm9 16H6V4h1v9l3-2.25L13 13V4h5v16z"/></svg>
                                <div>
                                    <span class="info-label">Snacks:</span>
                                    <span class="info-value">${signedUp ? `<strong>${signedUp}</strong>` : '<em>Not claimed</em>'}</span>
                                </div>
                            </div>
                            <div class="snack-form-group">
                                <input type="text" class="snack-input" id="input-${item.id}" placeholder="Enter name..." value="${signedUp}">
                                <button class="btn btn-gold" onclick="saveSnack('${item.id}')">Save</button>
                            </div>
                        </div>
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        async function saveSnack(id) {
            const inputElem = document.getElementById(`input-${id}`);
            if (!inputElem) return;
            const val = inputElem.value.trim();
            snackData[id] = val;

            localStorage.setItem("villa_soccer_snacks", JSON.stringify(snackData));
            renderGames();
            renderPractices();

            const status = document.getElementById('snackSyncNotice');
            if (status) status.innerText = "Syncing update...";

            try {
                const res = await fetch(JSONBIN_URL, {
                    method: 'PUT',
                    headers: {
                        "Content-Type": "application/json",
                        "X-Master-Key": API_KEY
                    },
                    body: JSON.stringify(snackData)
                });

                if (res.ok) {
                    if (status) status.innerText = "✓ Saved for everyone!";
                } else {
                    if (status) status.innerText = "✓ Saved locally!";
                }
            } catch (e) {
                if (status) status.innerText = "✓ Saved locally!";
            }

            setTimeout(() => { if (status) status.innerText = ""; }, 3000);
        }

        function downloadICS() {
            const icsData = `BEGIN:VCALENDAR
VERSION:2.0
PRODID:-//Villa Duchesne//2nd Grade Soccer Schedule//EN
CALSCALE:GREGORIAN
BEGIN:VEVENT
SUMMARY:Soccer: ST FRANCIS OF ASSISI SCHOOL (A)
DTSTART:20260830T190000Z
DTEND:20260830T200000Z
LOCATION:7600 Hazel Ave, St. Louis, MO 63119
DESCRIPTION:Field: Wehner - Odenwald, Field #1\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: MARY QUEEN OF PEACE SCHOOL (A)
DTSTART:20260912T180000Z
DTEND:20260912T190000Z
LOCATION:400 Magoffin Rd, St. Louis, MO 63129
DESCRIPTION:Field: Bussen Park, Field 1B\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: ST GABRIEL SCHOOL (A)
DTSTART:20260919T190000Z
DTEND:20260919T200000Z
LOCATION:11910 Eddie & Park Rd, St. Louis, MO 63126
DESCRIPTION:Location: ST JUSTIN THE MARTYR SCHOOL\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: ST MARGARET MARY ALACOQUE SCHOOL (A)
DTSTART:20260920T180000Z
DTEND:20260920T190000Z
LOCATION:4900 Ringer Rd, St. Louis, MO 63129
DESCRIPTION:Location: ST MARGARET MARY ALACOQUE SCHOOL\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: CHRIST THE KING CATHOLIC SCHOOL (A)
DTSTART:20260927T180000Z
DTEND:20260927T190000Z
LOCATION:3020 N Ballas Rd, St. Louis, MO 63131
DESCRIPTION:Location: Visitation Academy of St Louis\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: OUR LADY OF THE PILLAR SCHOOL (A)
DTSTART:20261004T180000Z
DTEND:20261004T190000Z
LOCATION:7600 Hazel Ave, St. Louis, MO 63119
DESCRIPTION:Location: Odenwald\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: MARY QUEEN OF PEACE SCHOOL (A)
DTSTART:20261017T200000Z
DTEND:20261017T210000Z
LOCATION:574 W Adams Ave, Kirkwood, MO 63122
DESCRIPTION:Field: Kirkwood Park, Upper Field A\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
BEGIN:VEVENT
SUMMARY:Soccer: ST GABRIEL SCHOOL (A)
DTSTART:20261025T180000Z
DTEND:20261025T190000Z
LOCATION:17 Joy Ave, Webster Groves, MO 63119
DESCRIPTION:Location: HOLY REDEEMER CATHOLIC SCHOOL\\nCoach: Matt Wootten (636-284-0190)\\nAssistant Coaches: Justin Lierz & Eddie Ibarra
END:VEVENT
END:VCALENDAR`;

            const blob = new Blob([icsData], { type: 'text/calendar;charset=utf-8' });
            const link = document.createElement('a');
            link.href = window.URL.createObjectURL(blob);
            link.setAttribute('download', '2nd_Grade_Soccer_Schedule.ics');
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        }

        window.onload = loadSnackData;
    </script>
</body>
</html>
