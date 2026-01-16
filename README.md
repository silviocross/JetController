<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JetController – Open Source RC Plane Controller</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            background: #0d1117;
            color: #e6edf3;
            line-height: 1.6;
        }

        header 10px;
            color: #58a6ff;
        }

        h2 {
            margin-top: 40px;
            color: #79c0ff;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 0 20px 40px 20px;
        }

        ul {
            margin-left: 20px;
        }

        .footer {
            text-align: center;
            padding: 20px;
            color: #8b949e;
            border-top: 1px solid #30363d;
            margin-top: 40px;
        }

        code {
            background: #161b22;
            padding: 3px 6px;
            border-radius: 6px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    logo.png
    <h1>JetController</h1>
    <p>An open‑source smart controller platform for RC planes (ESP32‑C3).</p>
</header>

<section>
    <h2>Overview</h2>
    <p>
        JetController is a fully open‑source hardware + firmware platform for RC aircraft,
        designed around the ESP32‑C3 and packed with advanced PWM, lighting, and
        high‑power output capabilities. The project includes hardware schematics, PCB layout,
        firmware developed in Arduino IDE, and 3D‑printable parts.
    </p>

    <h2>Main Features</h2>
    <ul>
        <li><strong>2× PWM Inputs</strong> – fully configurable (throttle, gear, lighting mode, etc.)</li>
        <li><strong>2× PWM Outputs</strong> – servo control or sequencing</li>
        <li><strong>3× LED Drivers</strong> – nav lights, beacon, landing lights, custom effects</li>
        <li><strong>2× High‑Power MOSFET Outputs</strong> – e.g., 7W afterburner LEDs</li>
        <li><strong>Wide Input Voltage</strong> – 5–30 V DC</li>
        <li><strong>Integrated BEC</strong> – 5 V @ 3 A</li>
        <li><strong>ESP32‑C3 Wi‑Fi</strong> – configuration UI (coming soon)</li>
    </ul>

    <h2>Included in the Repository</h2>
    <ul>
        <li>Hardware schematics (PDF + source)</li>
        <li>PCB layout files</li>
        <li>Arduino firmware</li>
        <li>3D‑printed housing models</li>
        <li>EDF afterburner adapter models</li>
    </ul>

    <h2>Bill of Materials (Main Components)</h2>
    <ul>
        <li>ESP32‑C3 SuperMini</li>
        <li>Mini step‑down regulator (5V)</li>
        <li>AO3401 MOSFETs (×5)</li>
        <li>Assorted discretes (resistors, capacitors, diodes)</li>
    </ul>

    <h2>License</h2>
    <p>
        This project is released under <strong>GPL‑3.0</strong>.  
        All derived work must remain open‑source.
    </p>
</section>

<div class="footer">
    JetController – Open Source RC Systems • GPL‑3.0
</div>

</body>
</html>
