<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pavan Kumar B - Networking & Validation Engineer</title>

<style>

@page {
    size: A4 landscape;
    margin: 10mm;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    color: #1f2937;
    background: #ffffff;
    font-size: 11px;
    line-height: 1.35;
}

.container {
    width: 100%;
    max-width: 1120px;
    margin: auto;
}

/* =========================
   HEADER
========================= */

.header {
    background: linear-gradient(135deg, #0b1f3a, #123e63);
    color: white;
    padding: 14px 20px 12px;
    border-radius: 8px;
    margin-bottom: 8px;
}

.header-name {
    font-size: 28px;
    font-weight: 800;
    letter-spacing: 1px;
    margin-bottom: 2px;
}

.header-title {
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 1.5px;
    color: #d7ecff;
}

.header-subtitle {
    font-size: 10px;
    margin-top: 5px;
    color: #e7f3ff;
}

.contact {
    display: table;
    width: 100%;
    margin-top: 9px;
    border-top: 1px solid rgba(255,255,255,0.25);
    padding-top: 7px;
}

.contact-item {
    display: table-cell;
    width: 25%;
    text-align: center;
    font-size: 9.5px;
    color: #ffffff;
}

/* =========================
   SECTION HEADERS
========================= */

.section {
    margin-top: 8px;
    margin-bottom: 6px;
}

.section-title {
    background: linear-gradient(90deg, #123e63, #1f6f9f);
    color: white;
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 0.8px;
    padding: 5px 10px;
    border-left: 5px solid #49a942;
    border-radius: 3px;
    margin-bottom: 6px;
    text-transform: uppercase;
}

/* =========================
   ABOUT
========================= */

.about {
    font-size: 10.5px;
    text-align: justify;
    margin: 0;
    padding: 2px 4px;
}

/* =========================
   HIGHLIGHTS
========================= */

.highlights {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 5px 0;
}

.highlight {
    display: table-cell;
    width: 25%;
    text-align: center;
    background: #f3f7fa;
    border: 1px solid #d7e1e8;
    border-top: 3px solid #1f6f9f;
    padding: 7px 4px;
    border-radius: 4px;
    font-size: 9.5px;
}

.highlight strong {
    display: block;
    font-size: 11px;
    color: #123e63;
}

.highlight span {
    font-size: 9px;
    color: #555;
}

/* =========================
   CORE COMPETENCIES
========================= */

.skills {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 5px 0;
}

.skill-box {
    display: table-cell;
    width: 25%;
    vertical-align: top;
    background: #fafcfd;
    border: 1px solid #d9e1e7;
    border-radius: 4px;
    padding: 7px;
    font-size: 9.5px;
}

.skill-title {
    color: #123e63;
    font-size: 10.5px;
    font-weight: bold;
    margin-bottom: 3px;
}

/* =========================
   TWO COLUMN AREA
========================= */

.two-column {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 8px 0;
}

.column {
    display: table-cell;
    width: 50%;
    vertical-align: top;
}

/* =========================
   EDUCATION
========================= */

.education {
    background: #f5f8fa;
    border-left: 4px solid #49a942;
    padding: 7px 10px;
    font-size: 10px;
}

/* =========================
   CAREER FOCUS
========================= */

.career {
    background: #eef5f9;
    border: 1px solid #d3e2eb;
    padding: 7px;
    text-align: center;
    font-size: 9.5px;
    color: #123e63;
    font-weight: 700;
}

/* =========================
   EXPERIENCE
========================= */

.experience {
    margin-bottom: 7px;
    border: 1px solid #dce4e9;
    border-radius: 4px;
    overflow: hidden;
}

.job-header {
    background: #f1f6f9;
    border-left: 5px solid #123e63;
    padding: 6px 9px;
}

.job-title {
    font-size: 11px;
    font-weight: 800;
    color: #123e63;
}

.job-date {
    font-size: 9px;
    color: #666;
    font-style: italic;
}

.job-content {
    padding: 5px 10px 4px;
}

.job-content ul {
    margin: 0;
    padding-left: 17px;
}

.job-content li {
    margin-bottom: 2px;
    font-size: 9.5px;
}

/* =========================
   VALIDATION FOCUS
========================= */

.validation {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 4px;
}

.validation-item {
    display: table-cell;
    width: 16.66%;
    text-align: center;
    background: #f5f8fa;
    border: 1px solid #d6e0e6;
    padding: 6px 2px;
    border-radius: 4px;
    color: #123e63;
    font-size: 9px;
    font-weight: bold;
}

/* =========================
   TECHNICAL TOOLKIT
========================= */

.toolkit {
    width: 100%;
    border-collapse: collapse;
    font-size: 9.5px;
}

.toolkit td {
    border: 1px solid #d8e0e6;
    padding: 4px 7px;
}

.toolkit td:first-child {
    width: 18%;
    background: #eef4f7;
    color: #123e63;
    font-weight: 800;
}

/* =========================
   PROCESS
========================= */

.process {
    margin-top: 8px;
    background: #123e63;
    color: white;
    text-align: center;
    padding: 7px;
    border-radius: 5px;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 0.4px;
}

/* =========================
   PROFESSIONAL TRAITS
========================= */

.traits {
    text-align: center;
    background: #f5f7f8;
    border: 1px solid #dce3e7;
    padding: 6px;
    margin-top: 6px;
    font-size: 9px;
    color: #374151;
}

/* =========================
   FOOTER
========================= */

.footer {
    margin-top: 7px;
    background: #0b1f3a;
    color: white;
    text-align: center;
    padding: 7px;
    border-radius: 5px;
    font-size: 9px;
}

.footer-name {
    font-size: 11px;
    font-weight: bold;
    margin-bottom: 2px;
}

.quote {
    color: #d7ecff;
    font-style: italic;
    margin-top: 3px;
}

/* =========================
   PRINT
========================= */

@media print {

    body {
        background: white;
    }

    .container {
        max-width: none;
    }

    .header,
    .section-title,
    .process,
    .footer {
        -webkit-print-color-adjust: exact;
        print-color-adjust: exact;
    }

    .experience {
        page-break-inside: avoid;
    }

    .skill-box,
    .highlight,
    .validation-item {
        page-break-inside: avoid;
    }
}

</style>
</head>

<body>

<div class="container">

<!-- =========================
     HEADER
========================= -->

<div class="header">

    <div class="header-name">
        PAVAN KUMAR B
    </div>

    <div class="header-title">
        NETWORKING &amp; VALIDATION ENGINEER
    </div>

    <div class="header-subtitle">
        Server Networking &nbsp;•&nbsp;
        Ethernet Validation &nbsp;•&nbsp;
        Linux &nbsp;•&nbsp;
        Python Automation
    </div>

    <div class="contact">

        <div class="contact-item">
            📍 Bengaluru, India
        </div>

        <div class="contact-item">
            📧 pavankumarbandhu@gmail.com
        </div>

        <div class="contact-item">
            📱 +91 9047215910
        </div>

        <div class="contact-item">
            💼 linkedin.com/in/YOUR_LINKEDIN
        </div>

    </div>

</div>


<!-- =========================
     ABOUT ME
========================= -->

<div class="section">

<div class="section-title">
    ABOUT ME
</div>

<p class="about">
Networking &amp; Validation Engineer with 3+ years turning complex network and
server-platform problems into reliable, well-tested systems. Currently at Intel,
validating Ethernet features, benchmarking throughput/latency, and stress-testing
server platforms under real-world conditions. I enjoy tracing packet drops and
latency spikes through firmware, silicon, and OS layers to the actual root cause —
then automating the fix with Python and Linux scripting so it stays fixed. Earlier
experience in enterprise networking sharpened my ability to stay calm under pressure
and troubleshoot live customer issues. Now looking for a team that values depth
over shortcuts.
</p>

</div>


<!-- =========================
     KEY HIGHLIGHTS
========================= -->

<div class="section">

<div class="section-title">
    KEY HIGHLIGHTS
</div>

<div class="highlights">

    <div class="highlight">
        🎯
        <strong>3+ Years</strong>
        <span>Networking &amp; Validation</span>
    </div>

    <div class="highlight">
        ⚙️
        <strong>Intel Server</strong>
        <span>Platform Validation</span>
    </div>

    <div class="highlight">
        🐍
        <strong>Automation-First</strong>
        <span>Python &amp; Linux Scripts</span>
    </div>

    <div class="highlight">
        🔍
        <strong>Root-Cause</strong>
        <span>Driven Troubleshooting</span>
    </div>

</div>

</div>


<!-- =========================
     CORE COMPETENCIES
========================= -->

<div class="section">

<div class="section-title">
    CORE COMPETENCIES
</div>

<div class="skills">

    <div class="skill-box">
        <div class="skill-title">🌐 Fundamentals</div>
        OSI · TCP/IP · IPv4/IPv6<br>
        TCP/UDP · ARP · ICMP<br>
        DNS · DHCP · NAT · CIDR
    </div>

    <div class="skill-box">
        <div class="skill-title">🔀 Switching</div>
        Ethernet · VLAN · 802.1Q<br>
        STP/RSTP · EtherChannel<br>
        LACP · MAC Learning
    </div>

    <div class="skill-box">
        <div class="skill-title">🧭 Routing</div>
        Static &amp; Default Routing<br>
        Inter-VLAN Routing<br>
        OSPF &amp; BGP Fundamentals
    </div>

    <div class="skill-box">
        <div class="skill-title">🔧 Troubleshooting</div>
        Packet Loss · Latency<br>
        DNS &amp; Routing Issues<br>
        Root Cause Analysis
    </div>

</div>

</div>


<!-- =========================
     EDUCATION + CAREER FOCUS
========================= -->

<div class="section">

<div class="two-column">

    <div class="column">

        <div class="section-title">
            EDUCATION
        </div>

        <div class="education">
            <b>Bachelor of Engineering</b><br>
            GRT Institute of Engineering and Technology<br>
            Anna University
        </div>

    </div>


    <div class="column">

        <div class="section-title">
            CAREER FOCUS
        </div>

        <div class="career">
            Network Engineer &nbsp;•&nbsp;
            Network Validation Engineer &nbsp;•&nbsp;
            Network Test Engineer &nbsp;•&nbsp;
            Server Networking Engineer &nbsp;•&nbsp;
            Network Automation Engineer
        </div>

    </div>

</div>

</div>


<!-- =========================
     PROFESSIONAL EXPERIENCE
========================= -->

<div class="section">

<div class="section-title">
    PROFESSIONAL EXPERIENCE
</div>


<div class="experience">

    <div class="job-header">

        <div class="job-title">
            Validation Engineer — Intel Server Platform
        </div>

        <div class="job-date">
            August 2023 – Present
        </div>

    </div>

    <div class="job-content">

        <ul>

            <li>
                Perform Ethernet and networking feature validation across server
                platform NICs, ensuring protocol compliance and stable link behavior
            </li>

            <li>
                Conduct throughput and latency analysis to benchmark performance
                against design targets
            </li>

            <li>
                Design and execute stress and reliability tests to surface
                intermittent hardware/firmware defects before production
            </li>

            <li>
                Own Linux-based validation and troubleshooting, isolating root
                causes across silicon, firmware, and OS layers
            </li>

            <li>
                Build Python/shell automation scripts to reduce manual test cycles
                and improve validation coverage
            </li>

            <li>
                Handle server bring-up, BIOS/BMC flashing and configuration,
                and platform-level debugging using JTAG and trace tools
            </li>

            <li>
                Track defects and document findings in Jira, producing clear
                validation reports for cross-functional teams
            </li>

        </ul>

    </div>

</div>


<div class="experience">

    <div class="job-header">

        <div class="job-title">
            Networking Engineer — TeamLease Services Limited
        </div>

        <div class="job-date">
            August 2022 – February 2023
        </div>

    </div>

    <div class="job-content">

        <ul>

            <li>
                Configured and monitored enterprise network infrastructure,
                ensuring consistent uptime and performance
            </li>

            <li>
                Diagnosed and resolved connectivity, latency, and packet-loss
                issues for internal and customer environments
            </li>

            <li>
                Managed service requests end-to-end, coordinating with customers
                and internal teams to meet SLAs
            </li>

            <li>
                Maintained detailed issue tracking and technical documentation
                to support recurring troubleshooting patterns
            </li>

        </ul>

    </div>

</div>

</div>


<!-- =========================
     VALIDATION FOCUS
========================= -->

<div class="section">

<div class="section-title">
    VALIDATION &amp; PERFORMANCE FOCUS
</div>

<div class="validation">

    <div class="validation-item">
        🌐<br>Ethernet
    </div>

    <div class="validation-item">
        📈<br>Throughput
    </div>

    <div class="validation-item">
        ⚡<br>Latency
    </div>

    <div class="validation-item">
        🧪<br>Stress
    </div>

    <div class="validation-item">
        🔄<br>Reliability
    </div>

    <div class="validation-item">
        🔍<br>Debugging
    </div>

</div>

</div>


<!-- =========================
     TECHNICAL TOOLKIT
========================= -->

<div class="section">

<div class="section-title">
    TECHNICAL TOOLKIT
</div>

<table class="toolkit">

<tr>
    <td>Networking</td>
    <td>
        Ethernet · TCP/IP · VLAN · Switching · Routing
    </td>
</tr>

<tr>
    <td>Systems</td>
    <td>
        Linux · Server Platforms · BIOS · BMC
    </td>
</tr>

<tr>
    <td>Automation</td>
    <td>
        Python · Shell Scripting
    </td>
</tr>

<tr>
    <td>Debugging</td>
    <td>
        JTAG · Trace Tools · Root Cause Analysis
    </td>
</tr>

<tr>
    <td>Platforms</td>
    <td>
        Intel Server Platforms · VMware · KVM
    </td>
</tr>

<tr>
    <td>Process</td>
    <td>
        Jira · Excel · Google Workspace
    </td>
</tr>

</table>

</div>


<!-- =========================
     ENGINEERING PROCESS
========================= -->

<div class="process">

IDENTIFY
&nbsp; → &nbsp;
ANALYZE
&nbsp; → &nbsp;
ROOT CAUSE
&nbsp; → &nbsp;
RESOLVE
&nbsp; → &nbsp;
VALIDATE
&nbsp; → &nbsp;
DELIVER

</div>


<!-- =========================
     PROFESSIONAL STRENGTHS
========================= -->

<div class="traits">

<b>
Problem Solving
&nbsp;•&nbsp;
Multitasking
&nbsp;•&nbsp;
Pressure Handling
&nbsp;•&nbsp;
Ownership
&nbsp;•&nbsp;
Discipline
&nbsp;•&nbsp;
Teamwork
&nbsp;•&nbsp;
Adaptability
&nbsp;•&nbsp;
Continuous Learning
</b>

</div>


<!-- =========================
     FOOTER
========================= -->

<div class="footer">

    <div class="footer-name">
        PAVAN KUMAR B
    </div>

    pavankumarbandhu@gmail.com
    &nbsp;|&nbsp;
    +91 9047215910
    &nbsp;|&nbsp;
    Bengaluru, Karnataka, India

    <div class="quote">
        "I don't just test the network — I understand it, troubleshoot it,
        validate it, and make it better."
    </div>

</div>

</div>

</body>
</html>
