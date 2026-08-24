<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pavan Kumar B - Networking & Validation Engineer</title>

<style>

/* =========================
   PAGE
========================= */

@page {
    size: A4 landscape;
    margin: 7mm;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    color: #202a35;
    background: #ffffff;
    font-size: 9px;
    line-height: 1.25;
}

.container {
    width: 100%;
    max-width: 1200px;
    margin: auto;
}


/* =========================
   HEADER
========================= */

.header {
    background: linear-gradient(135deg, #071d35, #0d4d78, #087f8c);
    color: white;
    padding: 11px 16px 9px;
    border-radius: 7px;
    margin-bottom: 5px;
}

.header-name {
    font-size: 25px;
    font-weight: 900;
    letter-spacing: 1.2px;
    margin-bottom: 1px;
}

.header-title {
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 1.4px;
    color: #7ee8ff;
}

.header-subtitle {
    font-size: 8.5px;
    margin-top: 3px;
    color: #e8faff;
}

.contact {
    display: table;
    width: 100%;
    margin-top: 6px;
    padding-top: 5px;
    border-top: 1px solid rgba(255,255,255,0.25);
}

.contact-item {
    display: table-cell;
    width: 25%;
    text-align: center;
    font-size: 8px;
    color: #ffffff;
}


/* =========================
   SECTION
========================= */

.section {
    margin-top: 5px;
    margin-bottom: 4px;
}

.section-title {
    background: linear-gradient(90deg, #063b66, #087f8c);
    color: #ffffff;
    font-size: 10px;
    font-weight: 900;
    letter-spacing: 0.8px;
    padding: 4px 8px;
    border-left: 4px solid #58d68d;
    border-radius: 3px;
    margin-bottom: 4px;
    text-transform: uppercase;
}


/* =========================
   ABOUT
========================= */

.about {
    font-size: 8.5px;
    text-align: justify;
    margin: 0;
    padding: 0 3px;
}

.highlight-blue {
    color: #0566a6;
    font-weight: 800;
}

.highlight-green {
    color: #159957;
    font-weight: 800;
}

.highlight-orange {
    color: #d97706;
    font-weight: 800;
}


/* =========================
   HIGHLIGHTS
========================= */

.highlights {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 4px 0;
}

.highlight {
    display: table-cell;
    width: 25%;
    text-align: center;
    background: #f5f9fb;
    border: 1px solid #d8e3e9;
    border-top: 2px solid #087f8c;
    padding: 5px 3px;
    border-radius: 3px;
    font-size: 8px;
}

.highlight strong {
    display: block;
    font-size: 9px;
    color: #063b66;
}

.highlight span {
    font-size: 7.5px;
    color: #58636d;
}


/* =========================
   CORE SKILLS
========================= */

.skills {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 4px 0;
}

.skill-box {
    display: table-cell;
    width: 25%;
    vertical-align: top;
    background: #fbfcfd;
    border: 1px solid #d8e1e6;
    border-radius: 3px;
    padding: 5px 6px;
    font-size: 8px;
}

.skill-title {
    color: #075985;
    font-size: 9px;
    font-weight: 900;
    margin-bottom: 2px;
}


/* =========================
   TWO COLUMNS
========================= */

.two-column {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 6px 0;
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
    background: #f5faf8;
    border-left: 4px solid #20a464;
    padding: 6px 9px;
    font-size: 8.5px;
    border-radius: 3px;
}

.degree {
    font-size: 10px;
    font-weight: 900;
    color: #063b66;
}

.cgpa {
    color: #159957;
    font-weight: 900;
}

.year {
    color: #d97706;
    font-weight: 900;
}


/* =========================
   CAREER FOCUS
========================= */

.career {
    background: #f2f8fb;
    border: 1px solid #d1e2eb;
    padding: 6px;
    text-align: center;
    font-size: 8px;
    color: #075985;
    font-weight: 800;
    border-radius: 3px;
}


/* =========================
   EXPERIENCE
========================= */

.experience {
    margin-bottom: 5px;
    border: 1px solid #d8e1e6;
    border-radius: 3px;
    overflow: hidden;
}

.job-header {
    background: linear-gradient(90deg, #eef6fa, #f7fbfd);
    border-left: 4px solid #087f8c;
    padding: 4px 7px;
}

.job-title {
    font-size: 9.5px;
    font-weight: 900;
    color: #063b66;
}

.job-date {
    font-size: 7.5px;
    color: #d97706;
    font-weight: 700;
}

.job-content {
    padding: 3px 8px 3px;
}

.job-content ul {
    margin: 0;
    padding-left: 15px;
}

.job-content li {
    margin-bottom: 1px;
    font-size: 8px;
}


/* =========================
   VALIDATION
========================= */

.validation {
    display: table;
    width: 100%;
    border-collapse: separate;
    border-spacing: 3px;
}

.validation-item {
    display: table-cell;
    width: 16.66%;
    text-align: center;
    background: #f5f9fb;
    border: 1px solid #d5e1e7;
    padding: 4px 2px;
    border-radius: 3px;
    color: #075985;
    font-size: 8px;
    font-weight: 900;
}


/* =========================
   TECHNICAL TOOLKIT
========================= */

.toolkit {
    width: 100%;
    border-collapse: collapse;
    font-size: 8px;
}

.toolkit td {
    border: 1px solid #d7e0e5;
    padding: 3px 6px;
}

.toolkit td:first-child {
    width: 17%;
    background: #edf5f8;
    color: #063b66;
    font-weight: 900;
}


/* =========================
   ENGINEERING PROCESS
========================= */

.process {
    margin-top: 5px;
    background: linear-gradient(90deg, #063b66, #087f8c);
    color: #ffffff;
    text-align: center;
    padding: 5px;
    border-radius: 4px;
    font-size: 8.5px;
    font-weight: 900;
    letter-spacing: 0.5px;
}


/* =========================
   PROFESSIONAL STRENGTHS
========================= */

.traits {
    text-align: center;
    background: #f7f9fa;
    border: 1px solid #dce3e7;
    padding: 4px;
    margin-top: 4px;
    font-size: 7.5px;
    color: #374151;
    border-radius: 3px;
}


/* =========================
   FOOTER
========================= */

.footer {
    margin-top: 5px;
    background: #071d35;
    color: white;
    text-align: center;
    padding: 5px;
    border-radius: 4px;
    font-size: 7.5px;
}

.footer-name {
    font-size: 9px;
    font-weight: 900;
    margin-bottom: 1px;
}

.quote {
    color: #8be8ff;
    font-style: italic;
    margin-top: 2px;
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

    .experience,
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

<span class="highlight-blue">
Networking &amp; Validation Engineer
</span>
with <b>3+ years</b> turning complex network and server-platform problems
into reliable, well-tested systems. Currently at <b>Intel</b>, validating
<span class="highlight-green">Ethernet features</span>, benchmarking
<span class="highlight-orange">throughput/latency</span>, and stress-testing
server platforms under real-world conditions. I enjoy tracing packet drops
and latency spikes through firmware, silicon, and OS layers to the actual
root cause — then automating the fix with <b>Python</b> and
<b>Linux scripting</b> so it stays fixed. Earlier experience in enterprise
networking sharpened my ability to troubleshoot live customer issues.
Now looking for a team that values <b>technical depth, automation and
reliable validation</b>.

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
        <span>Python &amp; Linux</span>
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

        <div class="skill-title">
            🌐 FUNDAMENTALS
        </div>

        OSI · TCP/IP · IPv4/IPv6<br>
        TCP/UDP · ARP · ICMP<br>
        DNS · DHCP · NAT · CIDR

    </div>


    <div class="skill-box">

        <div class="skill-title">
            🔀 SWITCHING
        </div>

        Ethernet · VLAN · 802.1Q<br>
        STP/RSTP · EtherChannel<br>
        LACP · MAC Learning

    </div>


    <div class="skill-box">

        <div class="skill-title">
            🧭 ROUTING
        </div>

        Static &amp; Default Routing<br>
        Inter-VLAN Routing<br>
        OSPF &amp; BGP Fundamentals

    </div>


    <div class="skill-box">

        <div class="skill-title">
            🔧 TROUBLESHOOTING
        </div>

        Packet Loss · Latency<br>
        DNS &amp; Routing Issues<br>
        Root Cause Analysis

    </div>

</div>

</div>


<!-- =========================
     EDUCATION + CAREER
========================= -->

<div class="section">

<div class="two-column">


    <div class="column">

        <div class="section-title">
            EDUCATION
        </div>

        <div class="education">

            <div class="degree">
                Bachelor of Engineering
            </div>

            GRT Institute of Engineering and Technology<br>

            Anna University &nbsp;|&nbsp;

            <span class="cgpa">
                CGPA: 8.7
            </span>

            &nbsp;|&nbsp;

            <span class="year">
                2022
            </span>

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


<!-- INTEL -->

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
                Perform Ethernet and networking feature validation across
                server platform NICs, ensuring protocol compliance and stable
                link behavior.
            </li>

            <li>
                Conduct throughput and latency analysis to benchmark
                performance against design targets.
            </li>

            <li>
                Design and execute stress and reliability tests to surface
                intermittent hardware/firmware defects before production.
            </li>

            <li>
                Own Linux-based validation and troubleshooting, isolating
                root causes across silicon, firmware, and OS layers.
            </li>

            <li>
                Build Python/shell automation scripts to reduce manual
                test cycles and improve validation coverage.
            </li>

            <li>
                Handle server bring-up, BIOS/BMC flashing and configuration,
                and platform-level debugging using JTAG and trace tools.
            </li>

            <li>
                Track defects and document findings in Jira, producing
                clear validation reports for cross-functional teams.
            </li>

        </ul>

    </div>

</div>


<!-- TEAMLEASE -->

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
                ensuring consistent uptime and performance.
            </li>

            <li>
                Diagnosed and resolved connectivity, latency, and packet-loss
                issues for internal and customer environments.
            </li>

            <li>
                Managed service requests end-to-end, coordinating with
                customers and internal teams to meet SLAs.
            </li>

            <li>
                Maintained detailed issue tracking and technical documentation
                to support recurring troubleshooting patterns.
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
        <b>Ethernet</b> · TCP/IP · VLAN · Switching · Routing
    </td>
</tr>

<tr>
    <td>Systems</td>
    <td>
        <b>Linux</b> · Server Platforms · BIOS · BMC
    </td>
</tr>

<tr>
    <td>Automation</td>
    <td>
        <b>Python</b> · Shell Scripting
    </td>
</tr>

<tr>
    <td>Debugging</td>
    <td>
        JTAG · Trace Tools · <b>Root Cause Analysis</b>
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
<span style="color:#7ee8ff;">ROOT CAUSE</span>
&nbsp; → &nbsp;
RESOLVE
&nbsp; → &nbsp;
<span style="color:#58d68d;">VALIDATE</span>
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
        "I don't just test the network — I understand it,
        troubleshoot it, validate it, and make it better."
    </div>

</div>


</div>

</body>
</html>
