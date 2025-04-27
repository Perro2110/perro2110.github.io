<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marco Perrotta | Software Developer</title>
    <style>
        :root {
            --primary-color: #0366d6;
            --secondary-color: #f1f8ff;
            --text-color: #24292e;
            --border-color: #e1e4e8;
            --hover-color: #f6f8fa;
            --shadow: 0 4px 12px rgba(0,0,0,0.08);
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: #fff;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        header {
            margin-bottom: 40px;
            text-align: center;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: var(--primary-color);
        }
        
        h2 {
            font-size: 1.8rem;
            margin: 40px 0 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--primary-color);
            color: var(--text-color);
        }
        
        h3 {
            font-size: 1.3rem;
            margin: 15px 0 10px;
            color: var(--text-color);
        }
        
        p {
            margin-bottom: 15px;
            text-align: justify;
        }
        
        .lead {
            font-size: 1.2rem;
            line-height: 1.7;
            margin: 20px 0 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 30px 0;
        }
        
        .social-links a {
            text-decoration: none;
            color: var(--primary-color);
            padding: 8px 16px;
            border-radius: 4px;
            transition: all 0.2s ease;
            font-weight: 500;
        }
        
        .social-links a:hover {
            background-color: var(--secondary-color);
            transform: translateY(-2px);
        }
        
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }
        
        .project-card {
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 24px;
            transition: all 0.3s ease;
            background-color: #fff;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow);
            border-color: var(--primary-color);
        }
        
        .project-card h3 {
            margin-top: 0;
            color: var(--primary-color);
        }
        
        .project-card p {
            margin: 10px 0;
            color: #586069;
        }
        
        .project-card a {
            display: inline-block;
            margin-top: 15px;
            color: var(--primary-color);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
        }
        
        .project-card a:hover {
            text-decoration: underline;
        }
        
        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .skill-tag {
            background: var(--secondary-color);
            border-radius: 16px;
            padding: 6px 14px;
            font-size: 0.9rem;
            color: var(--primary-color);
            font-weight: 500;
            transition: all 0.2s ease;
        }
        
        .skill-tag:hover {
            background-color: var(--primary-color);
            color: white;
            transform: translateY(-2px);
        }
        
        .education {
            margin: 30px 0;
        }
        
        .education-item {
            margin-bottom: 25px;
        }
        
        .education-item h3 {
            margin-bottom: 5px;
        }
        
        .education-item .degree {
            font-weight: 600;
            color: #586069;
        }
        
        .education-item .period {
            font-style: italic;
            color: #586069;
            margin: 5px 0;
        }
        
        .education-item .grade {
            display: inline-block;
            background-color: var(--secondary-color);
            padding: 2px 8px;
            border-radius: 4px;
            color: var(--primary-color);
            font-weight: 500;
            margin-top: 5px;
        }
        
        .publications {
            margin: 30px 0;
        }
        
        .publication-item {
            padding: 20px;
            border-left: 3px solid var(--primary-color);
            background-color: var(--hover-color);
            margin-bottom: 20px;
            border-radius: 0 8px 8px 0;
        }
        
        .publication-item h3 {
            margin-top: 0;
        }
        
        .publication-item a {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: 500;
        }
        
        .publication-item a:hover {
            text-decoration: underline;
        }
        
        footer {
            text-align: center;
            margin-top: 60px;
            padding-top: 20px;
            border-top: 1px solid var(--border-color);
            color: #586069;
        }
        
        @media (max-width: 768px) {
            .project-grid {
                grid-template-columns: 1fr;
            }
            
            .social-links {
                flex-direction: column;
                align-items: center;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Marco Perrotta</h1>
            <div class="lead">
                Software Developer specializzato in soluzioni di Machine Learning ed implementazioni ottimizzate, con focus sulla ricerca e sviluppo di framework per l'apprendimento automatico interpretabile.
            </div>
            <div class="social-links">
                <a href="mailto:perrottamarco2011@gmail.com">📧 perrottamarco2011@gmail.com</a>
                <a href="https://github.com/Perro2110">🐙 GitHub</a>
                <a href="https://linkedin.com/in/marco-perrotta-b159b6244">💼 LinkedIn</a>
            </div>
        </header>
        
        <section id="about">
            <h2>Chi Sono</h2>
            <p>Nato a Pozzuoli e cresciuto a Ferrara, ho coltivato sin dall'adolescenza una forte passione per l'informatica e le scienze computazionali. Il mio interesse per i sistemi informativi si è gradualmente evoluto in una specializzazione professionale nell'ambito dell'intelligenza artificiale e della programmazione avanzata.</p>
            
            <p>Attualmente, il mio focus di ricerca è incentrato sullo sviluppo di Sole.jl, un framework innovativo per l'apprendimento automatico interpretabile (IML) implementato in Julia. In questo progetto, collaboro attivamente con un team di ricercatori per migliorare la trasparenza e l'interpretabilità degli algoritmi di machine learning.</p>
            
            <p>La mia formazione unisce una solida base matematica teorica con competenze tecniche di implementazione algoritmica. Questo approccio interdisciplinare mi permette di affrontare efficacemente sfide complesse nell'ottimizzazione delle implementazioni e nello sviluppo di soluzioni innovative per il machine learning.</p>
        </section>
        
        <section id="projects">
            <h2>Progetti di Ricerca</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>🕯️ Lumen</h3>
                    <p><strong>Logic-driven Unified Minimal Extractor of Notions</strong></p>
                    <p>Algoritmo innovativo per l'estrazione di conoscenza da modelli di machine learning complessi, con focus sulla minimizzazione delle regole e sull'interpretabilità.</p>
                    <div class="skill-tags">
                        <span class="skill-tag">Julia</span>
                        <span class="skill-tag">Algoritmi Interpretabili</span>
                    </div>
                    <a href="https://github.com/aclai-lab/SolePostHoc.jl">Visualizza Progetto →</a>
                </div>
                
                <div class="project-card">
                    <h3>☀️ Sole Framework</h3>
                    <p><strong>Symbolic, Transparent, and Interpretable Machine Learning</strong></p>
                    <p>Framework completo per lo sviluppo di sistemi di apprendimento automatico simbolici e trasparenti, progettato per garantire la comprensibilità dei processi decisionali.</p>
                    <div class="skill-tags">
                        <span class="skill-tag">Julia</span>
                        <span class="skill-tag">Machine Learning</span>
                        <span class="skill-tag">Interpretabilità</span>
                    </div>
                    <a href="https://github.com/aclai-lab/Sole.jl">Visualizza Progetto →</a>
                </div>

                <div class="project-card">
                    <h3>📚 SolePostHoc</h3>
                    <p><strong>Post-hoc Interpretability Library</strong></p>
                    <p>Libreria specializzata per l'implementazione di algoritmi di interpretabilità post-hoc, con particolare attenzione all'estrazione di nozioni chiave da modelli complessi.</p>
                    <div class="skill-tags">
                        <span class="skill-tag">Julia</span>
                        <span class="skill-tag">Algoritmi Post-hoc</span>
                        <span class="skill-tag">Interpretabilità</span>
                    </div>
                    <a href="https://github.com/aclai-lab/SolePostHoc.jl">Visualizza Progetto →</a>
                </div>
            </div>
        </section>
        
        <section id="skills">
            <h2>Competenze Tecniche</h2>
            <div class="skill-tags">
                <span class="skill-tag">C</span>
                <span class="skill-tag">Java</span>
                <span class="skill-tag">Julia</span>
                <span class="skill-tag">Haskell</span>
                <span class="skill-tag">Unix-like OS</span>
                <span class="skill-tag">Git</span>
                <span class="skill-tag">MySQL</span>
                <span class="skill-tag">Laravel</span>
                <span class="skill-tag">Machine Learning</span>
                <span class="skill-tag">Algoritmi di ottimizzazione</span>
                <span class="skill-tag">Programmazione funzionale</span>
            </div>
        </section>
        
        <section id="education">
            <h2>Formazione Accademica</h2>
            <div class="education">
                <div class="education-item">
                    <h3>Università degli Studi di Ferrara</h3>
                    <div class="degree">Laurea Triennale in Informatica</div>
                    <div class="period">In corso</div>
                    <p>Curriculum incentrato su algoritmi avanzati, machine learning e fondamenti matematici dell'informatica.</p>
                </div>
                
                <div class="education-item">
                    <h3>IIS N.Copernico A.Carpeggiani</h3>
                    <div class="degree">Diploma in Scienze Informatiche</div>
                    <div class="period">2017 - 2022</div>
                    <p>Formazione specialistica in programmazione, architetture di sistema e progettazione software.</p>
                    <span class="grade">🎓 Votazione: 100/100 cum laude</span>
                </div>
            </div>
        </section>
        
        <section id="publications">
            <h2>Pubblicazioni Scientifiche</h2>
            <div class="publications">
                <div class="publication-item">
                    <h3><a href="https://overlay.uniud.it/workshop/2024/papers/paper14.pdf">Minimal Rules from Decision Forests: a Systematic Approach</a></h3>
                    <p>Ricerca innovativa che propone una formalizzazione matematica rigorosa del problema dell'estrazione di regole minime da foreste decisionali, presentando un approccio sistematico per migliorare l'interpretabilità dei modelli ensemble complessi.</p>
                </div>
            </div>
        </section>
        
        <footer>
            <p>&copy; 2025 Marco Perrotta. Tutti i diritti riservati.</p>
        </footer>
    </div>
</body>
</html>
