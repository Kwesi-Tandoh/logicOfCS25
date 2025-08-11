
# CE 474 — Logic of Computer Science  
University of Mines and Technology · Department of Computer Science & Engineering  
Semester 2 · 2025 · 2 Credits (1 × 2-hour session / week)


Welcome to the official course repository for **CE 47: Logic of Computer Science**.  
Here you will find everything you need to follow the course, stay on track with deadlines, and deepen your understanding of formal logic and its applications in computer science.


## 📌 Quick Facts
| Item | Details |
|------|---------|
| **Instructor** | **Dr. Sylvester Akpah** · sakpah@umat.edu.gh · +233 20-754-1684 |
| **Demonstrator** | **Emmanuel Kwesi Tandoh** · pg-ektandoh7023@st.umat.edu.gh · +233 557-511-017 |
| **Prerequisites** | Senior standing (Year 4) in BSc Computer Science & Engineering; prior course in Discrete Mathematics |
| **Primary Text** | Huth & Ryan, *Logic in Computer Science* (3rd ed.) |
| **Optional Tools** | SWI-Prolog, Prover9/Mace4, Z3 SMT Solver |
| **Credits** | 2 (meets once per week, 2 hrs) |
| **Syllabus PDF** | [`outline/course-outline.pdf`](outline/course-outline.pdf) |

---

## 🎯 Learning Outcomes
By the end of the semester you will be able to:

1. **Master propositional & predicate logic** – formally specify statements and interpret semantics.  
2. **Construct & critique formal proofs** – apply natural deduction, direct, contrapositive, and contradiction methods.  
3. **Apply logic to CS problems** – perform resolution, SAT solving, and write simple Prolog programs.  
4. **Communicate logical arguments effectively** – present and defend positions in class debates.  
5. *(Optional)* **Use automated reasoning tools** – encode theorems in Prover9 or an SMT solver such as Z3.

---

## 📂 Repository Layout

| Folder / File | Contents | Format |
|---------------|----------|--------|
| **`slides/`** | Weekly lecture decks (`week##-topic.pdf/md`) | `.pdf`, `.md` |
| **`notes/`** | Detailed LaTeX notes + compiled PDFs | `.tex`, `.pdf` |
| **`problems/`** | Problem sets & official solutions | `.pdf`, `.tex` |
| **`books/`** | Open-access textbooks, articles, reference sheets | `.pdf`, `.epub` |
| **`outline/`** | Syllabus (`course-outline.pdf`) & milestone calendar | `.pdf` |
| **`utilities/`** | Build scripts, TikZ diagram helpers, LaTeX class/style files | `.sh`, `.py`, `.cls` |
| **`README.md`** | Start-here guide (this file) | `.md` |

> **Clone tip** — if bandwidth is tight:  
> `git clone --depth 1 https://github.com/<org>/logic-of-cs-ce474.git`

---

## 📅 Weekly Roadmap

| Wk | Theme | In-Class Focus | Deliverables (due following week unless stated) |
|----|-------|----------------|-----------------------------------------------|
| 1 | Foundations & Set Theory Review | Set-proof race | **PS 1** – Set identities proofs |
| 2 | Propositional Logic: Syntax & Semantics | Truth tables, tautology checks | **Quiz 1**, **PS 2** – English ↔ formula translation |
| 3 | Natural Deduction | Relay proof game | **PS 3** – Five derivations |
| 4 | Predicate Logic: Quantifiers & Domains | Translating ∀/∃ | **Quiz 2**, **PS 4** – Quantifier proofs |
| 5 | Proof Techniques & Strategy | Direct, contrapositive, contradiction | **PS 5**, mini-project proposal |
| 6 | Soundness & Completeness | Proof sketches | **PS 6**, debate prep |
| 7 | Resolution & SAT Solving | CNF resolution, DPLL walkthrough | **PS 7** – SAT encodings |
| 8 | Logic Programming in Prolog | Prolog search trees | **PS 8**, project checkpoint |
| 9 | Hoare Logic & Model Checking | Hoare triples, model checking demo | **PS 9**, project draft |
| 10 | Review & Presentations | Final quiz & capstone presentations | Final submission |

*A more granular timeline (with exact dates) is inside `outline/course-outline.pdf`.*

---

## 📝 Assessment & Grading

| Component | Weight |
|-----------|--------|
| Quizzes (2 ×) | 10 % |
| Problem Sets (best 8 of 9) | 10 % |
| Debates | 15 % |
| Participation | 5 % |
| **Continuous Assessment subtotal** | **40 %** |
| Final Exam | 30 % |
| Final Project | 30 % |
| **Total** | **100 %** |

**Grade Scale** – A ≥ 85, B 70–84, C 55–69, D 45–54, F < 45.

---

## 📜 Policies

* **Late Work** – Up to 48 h late for 10 % penalty; afterwards not accepted.  
* **Academic Integrity** – Assignments must be your own; credit all collaboration.  
* **Accessibility** – Contact the instructor early to arrange accommodations.  
* **Communication** – Announcements via LMS; critical notices duplicated in GitHub Issues.  
* **Repo Etiquette** – This repository is **read-only for students**. Do **not** push solutions before release. Typo/clarification PRs are welcome.

---

## 🚀 Quick Start for Local Builds

```bash
# 1. Clone
git clone https://github.com/<org>/logic-of-cs-ce474.git
cd logic-of-cs-ce474

# 2. Build LaTeX notes (requires TeX Live / MiKTeX)
./utilities/build-notes.sh week03      # one week
./utilities/build-notes.sh all         # everything
