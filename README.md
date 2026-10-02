# Billal Tbaili

Computer Science undergraduate at the University of Electronic Science and Technology of
China (UESTC), graduating in June 2027. I like building small, well-tested software and
working with data and security.

## Featured project: PaperSearch

[PaperSearch][papersearch] is a search engine over 100,000 computer science papers from
arXiv. The inverted index, BM25 ranking, autocomplete trie and spelling correction are
written from scratch, without a search library, and the results are measured:

- **Ranking quality:** given only a paper's title, it ranks that paper first 85.1% of the
  time (MRR@10 0.885), against 65.6% for counting matching words and 24.1% for raw term
  frequency.
- **Speed:** a full search takes 6.7 ms at the median over 9.1 million postings, including
  ranking every matching paper and building the snippets.
- **Engineering:** SQLite or PostgreSQL, a REST API and web page, Docker Compose, tests and CI.

## Projects

| Project | What it is | Built with |
|---------|------------|------------|
| [PaperSearch][papersearch] | A search engine over 100,000 computer science papers, with ranking, autocomplete and spelling correction written from scratch | Python, FastAPI, PostgreSQL, Docker |
| [Phishing Email Detector][phishing] | A machine learning model that labels an email as phishing or safe, with 98.3% accuracy on 3,508 real emails it was not trained on | Python, scikit-learn, pandas |
| [Secure Login][login] | A login web app with Argon2id password hashing, server-side sessions, two-factor authentication and protection against guessing | Python, Flask, SQLite |
| [Vulnerability Scanner][scanner] | A scanner that checks a host or web site for open ports, weak configuration and outdated software, and writes a report with fixes | Python, standard library only |
| [Password Strength Analyzer][password] | A desktop and command-line tool that rates passwords, suggests stronger ones and refuses reused ones | Python, Tkinter, SQLite |
| [Fee Report][fee] | A student fee management desktop application with admin and accountant logins and a due fee report | Java, Swing, SQLite |

Every project has automated tests that run on GitHub Actions.

## Education

**Bachelor's degree in Computer Science and Technology** (expected June 2027)<br>
School of Computer Science and Engineering, University of Electronic Science and
Technology of China, Chengdu<br>
English-taught program, August 2023 to June 2027

## Skills

| Area | Tools | Where to see it |
|------|-------|-----------------|
| Languages | Python, Java, SQL | Python in five projects, Java in [Fee Report][fee], SQL in every project with a database |
| Information retrieval | Inverted index, BM25 ranking, tries, spelling correction | [PaperSearch][papersearch] |
| Machine learning | scikit-learn, pandas | [Phishing Email Detector][phishing] |
| Web and APIs | FastAPI, Flask | [PaperSearch][papersearch], [Secure Login][login] |
| Desktop | Swing, Tkinter | [Fee Report][fee], [Password Strength Analyzer][password] |
| Databases | PostgreSQL, SQLite | [PaperSearch][papersearch] (both), [Secure Login][login], [Password Strength Analyzer][password], [Fee Report][fee] |
| Security | Argon2id password hashing, two-factor authentication, port and web site scanning, phishing detection, password strength estimation | [Secure Login][login], [Vulnerability Scanner][scanner], [Phishing Email Detector][phishing], [Password Strength Analyzer][password] |
| Engineering | Git, GitHub Actions, Docker, automated testing | Tests and CI in every project, Docker in [PaperSearch][papersearch] |
| Foundations | Data structures, algorithms, computer architecture, discrete mathematics | UESTC coursework and the Codecademy certification below |

## Certifications

| Certification | Issuer | Date |
|---------------|--------|------|
| Computer Science, Professional Certification | Codecademy | September 2026 |
| Analyze Data with Microsoft Excel | Codecademy | September 2026 |

The Computer Science certification is awarded for passing exams in programming, data
structures, algorithms, trees and graphs, databases, computer architecture and
mathematics for computer science.

[papersearch]: https://github.com/TBAILIBILLAL/papersearch
[phishing]: https://github.com/TBAILIBILLAL/phishing-detector
[login]: https://github.com/TBAILIBILLAL/secure-login
[scanner]: https://github.com/TBAILIBILLAL/vulnerability-scanner
[password]: https://github.com/TBAILIBILLAL/password-analyzer
[fee]: https://github.com/TBAILIBILLAL/fee-report
