<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --bg-color: #f8fafc;
            --text-color: #1e293b;
            --card-bg: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
            color: white;
            padding: 5rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            letter-spacing: -1px;
        }

        header p {
            font-size: 1.25rem;
            color: #94a3b8;
        }

        .container {
            max-width: 800px;
            margin: -3rem auto 3rem;
            padding: 0 1rem;
        }

        section {
            background: var(--card-bg);
            padding: 2.5rem;
            border-radius: 12px;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        h2 {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 1rem;
        }

        .skill-badge {
            background: #eff6ff;
            color: #1e40af;
            padding: 0.5rem;
            border-radius: 6px;
            text-align: center;
            font-size: 0.9rem;
            font-weight: 600;
        }

        .project-card {
            border-bottom: 1px solid #e2e8f0;
            padding: 1.5rem 0;
        }

        .project-card:last-child {
            border-bottom: none;
        }

        .project-card h3 {
            margin-bottom: 0.5rem;
        }

        .contact-info p {
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #64748b;
        }

        @media (max-width: 600px) {
            header h1 { font-size: 2.2rem; }
