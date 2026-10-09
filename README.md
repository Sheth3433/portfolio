# Aarjav Sheth — Portfolio

Aarjav Sheth માટેનું responsive single-page developer portfolio. નવા designમાં અગાઉ પસંદ કરેલી warm off-white અને blue palette જાળવીને blue hero/contact panels, image-led composition, categorized skill cards અને featured project layout ઉમેર્યાં છે. હેતુ સાદા સફેદ pageમાં text મૂકવાનો નહીં, પરંતુ compact, visual hierarchy ધરાવતો અને mobile પર પણ ગોઠવાયેલો portfolio બનાવવાનો છે.

## Master design prompt

આ redesign માટે બનાવેલો reusable, detailed master prompt [DESIGN-PROMPT.md](./DESIGN-PROMPT.md)માં છે. તેમાં visual direction, content-preservation rules, sections, responsive behavior અને quality checks નોંધેલા છે.

`https://www.influconnect.in/`ને reference તરીકે જોઈને high-contrast hero, સ્પષ્ટ calls to action અને sectionsની visual rhythmમાંથી પ્રેરણા લેવાઈ છે. Reference siteની branding, text, assets કે ચોક્કસ layout copy કર્યાં નથી.

## Project structure

```text
Portfolio/
├── DESIGN-PROMPT.md
├── CONTACT-FORM-SETUP.md
├── README.md
├── portfolio.html
└── assets/
    ├── icons/
    │   └── leetcode
    ├── images/
    │   ├── aarjav.jpeg
    │   ├── aarjav1.jpeg
    │   ├── aarjav2.jpeg
    │   └── aarjav3.jpeg
    ├── certificates/
    │   ├── Agile_Scrum_Master.jpg
    │   ├── AI_ML.jpeg
    │   ├── AIT.jpeg
    │   ├── AWS.jpeg
    │   ├── Completion_Certificate.jpeg
    │   ├── Hour_of_AI.jpeg
    │   └── Java.jpeg
    └── resume/
        └── Aarjav_Resume.pdf
```

Heroમાં `aarjav3.jpeg`, Aboutમાં `aarjav2.jpeg`, certificate sectionમાં છ credential images, Experienceમાં BrainyBeam internship, Educationમાં AIT Hackathon highlight અને બંનેના certificate previews, અને resume actionsમાં PDF વપરાય છે. `aarjav.jpeg`, `aarjav1.jpeg` અને `assets/icons/leetcode` હાલની redesignમાં વપરાતા નથી. Relative paths જળવાઈ રહે તે માટે assetsનું folder structure જાળવો.

## Technologies

- **HTML5:** Semantic navigation, main, sections, articles, lists, forms અને footer.
- **CSS3:** એ જ HTMLના `<style>`માં design tokens, grid/flex layouts, responsive breakpoints, hover/focus feedback, subtle hero/scroll animations અને reduced-motion support.
- **Vanilla JavaScript:** Accessible mobile menu, active-section navigation, scroll reveal, certificate preview dialog અને prefilled email draft form action.
- **Google Fonts:** Inter CDN પરથી લોડ થાય છે; offline હોય તો Arial fallback વપરાય છે.

કોઈ framework, build step અથવા package manager નથી. Font સિવાય runtime CDN libraryની જરૂર નથી.

## Page sections

1. **Navigation:** Sticky header, section links, highlighted Resume download અને mobile hamburger menu.
2. **Hero:** Blue image-led panel, role, પરિચય, project/resume actions અને profile portrait; નીચે projects, skill domains, certificates અને internshipના count દર્શાવતો compact strip.
3. **About:** Profile image અને bio સાથે Education, Experience અને Locationના નાના information cards.
4. **Skills:** છ categories — Programming, Web Development, Mobile Development, Database, AI/Machine Learning અને Tools — દરેકને compact tag cardમાં દર્શાવાય છે.
5. **Projects:** પાંચ repository-backed cards — Object Detection for Blind People, AI Resume Scanner & Job Matcher, Spotify YouTube Sync Automation, Traffic Control Management System અને Podcast Recommendation System. દરેકમાં repository link અને ઓળખી શકાય તેવી technologies છે.
6. **Experience & Education:** Android internship timeline/panel અને હાલના HTMLની education values ધરાવતો compact academic panel. Education panelની ખાલી જગ્યા AIT Hackathon highlightથી ભરાય છે: EduTech Event & Exam Planner, timetable OCR, AI study plans, reminders/collaborative calendars અને Flutter/Firebase/Node.js/API-Ninjas/Gemini AI stack. BrainyBeam completion તથા AIT participation certificates inline preview, modal preview અને download સાથે છે.
7. **Certificates:** user-provided છ credentials — Agile Scrum Master (Simplilearn), AWS Academy Graduate - Cloud Foundations, Hours of AI, Green Skills and Artificial Intelligence, Introduction to Java (LearnQuest) અને AIT Hackathon participation. દરેક credentialનું original local image cardમાં દેખાય છે; image ખોલીને મોટું preview અથવા download કરી શકાય છે. Issuer/date/આપેલા credential IDs તથા માત્ર મળેલા verification links જ દર્શાવાય છે.
8. **Contact:** Blue contact panelમાં email, phone, location, social links અને validation ધરાવતું feedback/contact form. Submit પર visitorના email appમાં name, reply email, subject અને message ભરેલો draft ખુલે છે; visitorએ email પોતે send કરવો રહે છે.
9. **Footer:** Copyright, technology credit અને back-to-top link.

## Certificate records

આ વિગતો portfolio owner દ્વારા આપવામાં આવી છે. Credential IDs/URLs આપવામાં ન હોય ત્યાં કોઈ ID કે verification link બનાવ્યો નથી.

| Certificate | Image file | Issuer/organizer | Issued/event date | Credential ID |
| --- | --- | --- | --- | --- |
| Agile Scrum Master | `Agile_Scrum_Master.jpg` | Simplilearn | Jul 2026 | `10517333` |
| AWS Academy Graduate - Cloud Foundations | `AWS.jpeg` | Amazon Web Services (AWS) | Apr 2026 | Not supplied |
| Hours of AI | `Hour_of_AI.jpeg` | GLS ACM Student Chapter | Dec 2025 | Not supplied |
| Green Skills and Artificial Intelligence | `AI_ML.jpeg` | Skills4Future | Jul 2025 | Not supplied |
| Introduction to Java | `Java.jpeg` | LearnQuest | Aug 2024 | `69J7KGI866BT` |
| AIT Hackathon · Participation | `AIT.jpeg` | Ahmedabad Institute of Technology | Event: 2 Aug 2025 | Not supplied |

Verification links: [Simplilearn](https://www.simplilearn.com/skillup-certificate-landing?token=eyJjb3Vyc2VfaWQiOiI0NDgzIiwiY2VydGlmaWNhdGVfdXJsIjoiaHR0cHM6XC9cL2NlcnRpZmljYXRlcy5zaW1wbGljZG4ubmV0XC9zaGFyZVwvMTA1MTczMzNfMTA4Mzk2MTJfMTc4NTEzMDIxNjM1OC5wbmciLCJ1c2VybmFtZSI6IkFhcmphdiBTaGV0aCJ9&utm_source=shared-certificate&utm_medium=lms&utm_campaign=shared-certificate-promotion&referrer=https%3A%2F%2Flms.simplilearn.com%2Fcourses%2F7411%2FAgile-Scrum-Master_SkillUp%2Fcertificate%2Fdownload-skillup&%24web_only=true&_branch_match_id=1472162743341860569&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXL87MLcjJ1EssKNDLyczL1k%2FVN6r0DQuLTPQ0M0myrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAuCcPpD8AAAA%3D), [AWS Credly](https://www.credly.com/go/bJRG7ags), [Coursera](https://www.coursera.org/account/accomplishments/verify/69J7KGI866BT).

The BrainyBeam Android internship completion certificate is the original `assets/certificates/Completion_Certificate.jpeg` image. It records the internship from 15 May to 13 June 2026 and is shown inline, in an accessible native dialog, and as a downloadable JPEG.

The owner-provided AIT highlight says the team built **EduTech**, an event/exam planner, in under 48 hours. The portfolio summary covers image-based exam timetable OCR, personalized AI study plans, reminders, shared schedules, and collaborative calendars. The supplied participation certificate image records the AIT Hackathon on 2 Aug 2025; no award or winning placement is claimed.

## Selected GitHub projects

The selection is based on public repositories under [github.com/Sheth3433](https://github.com/Sheth3433); descriptions and technology labels reflect repository metadata, README content, and visible files.

| Project | Repository | What it does | Stack shown |
| --- | --- | --- | --- |
| Object Detection for Blind People | [GitHub](https://github.com/Sheth3433/Object-Detection-for-Blind-People) | Assistive mobile app for object detection, OCR, currency recognition, voice interaction, and navigation support. | Flutter, Dart, Python, OpenCV, YOLOv8, EasyOCR |
| AI Resume Scanner & Job Matcher | [GitHub](https://github.com/Sheth3433/AI_Resume_Scanner_System) | Local-first resume/job-description analysis with ATS estimates, comparisons, skill-gap guidance, and saved analyses. | React, Vite, FastAPI, Python |
| Spotify YouTube Sync Automation | [GitHub](https://github.com/Sheth3433/spotify-youtube-sync-automation) | n8n workflow to sync Spotify liked songs to a YouTube playlist. | n8n, Spotify, YouTube |
| Traffic Control Management System | [GitHub](https://github.com/Sheth3433/Traffic-Control-Management-System) | Web application covering traffic monitoring, signal management, challans, emergency coordination, search, and analytics. | PHP, MySQL |
| Podcast Recommendation System | [GitHub](https://github.com/Sheth3433/podcast-recommendations-system) | Podcast suggestions based on interests and listening preferences. | Dart, recommendation system |

## Visual design

### રંગો અને typography

| હેતુ | રંગ |
| --- | --- |
| Warm page background | `#F8F8F6` |
| Surface/card | `#FFFFFF` |
| Primary text | `#171717` |
| Secondary text | `#666666` |
| Muted text | `#888888` |
| Border | `#E7E7E4` |
| Primary blue | `#315CFF` |
| Pale blue | `#EEF2FF` |

Inter મુખ્ય font છે. Blue hero અને contact panels મુખ્ય visual anchors છે; pale blue skills/certificate band, numbered project cards, compact fact cards અને photo framing designને ફક્ત plain-white text layout બનવાથી બચાવે છે. Heroમાં text/photo entrance, photoનું બહુ હળવું float, decorative orbit અને scroll પર section/card reveal ઉમેર્યાં છે. Gradient/neon glow, particle background, cursor effects અને loader નથી.

Colors, container width, header height, section spacing, radius અને transition CSS custom properties દ્વારા નિયંત્રિત થાય છે. Componentsમાં સામાન્ય રીતે 10–16px corner radius, subtle borders અને બહુ હળવા hover shadows છે.

### Layout અને section spacing

- મુખ્ય content containerની મહત્તમ પહોળાઈ 1180px છે.
- Desktop પર hero, About, Skills અને Contactમાં balanced columns; projectsમાં એક featured અને ચાર supporting cards.
- Experience અને education compact side-by-side panelsમાં છે; certificate image cards ત્રણ columnsમાં ગોઠવાય છે.
- Section spacing સામાન્ય રીતે આશરે 56–85px desktop અને 56px mobile છે; સંબંધિત વિગતો cardsની અંદર વધુ નજીક રાખવામાં આવી છે.
- Heroની blue surface અને white project/contact areas વચ્ચેનો contrast section rhythm બનાવે છે.

### Responsive behavior

- **1100px અને નીચે:** Navigation spacing તથા hero dimensions અનુકૂળ થાય છે.
- **900px અને નીચે:** Desktop navigation/resume link mobile menuમાં જાય છે.
- **680px અને નીચે:** Heroમાં text અને portrait compact side-by-side, Aboutમાં photo અને copy બે columnsમાં, skill/project layouts mobile gridમાં, અને contact panel એક columnમાં ગોઠવાય છે.
- **390px અને નીચે:** Hero portrait/heading columns વધુ compact થાય છે, form fields stack થાય છે અને footer vertical બને છે.
- **340px અને નીચે:** About section photo ઉપર અને copy નીચે ગોઠવાય છે.

Responsive CSS targetsમાં 1440, 1280, 1024, 768, 480, 390 અને 375pxનો સમાવેશ થાય છે. Browser/device emulationમાં CSS viewport actual widthથી અલગ હોઈ શકે છે; તેથી વાસ્તવિક `innerWidth` અને `scrollWidth` જોઈને overflow તપાસવો.

## JavaScript અને accessibility

- Hamburger menu `aria-expanded` અને accessible label update કરે છે; link click અથવા Escapeથી menu બંધ થાય છે. Escape સમયે focus menu button પર પાછું આવે છે.
- `IntersectionObserver` visible section પ્રમાણે navigation link active કરે છે.
- એ જ observer section headings અને cardsને એકવાર reveal કરે છે; project અને certificate cardsનો reveal હળવો stagger થાય છે.
- Certificate cardsમાં local image preview, accessible dialog, Escape/click-to-dismiss અને image download controls છે.
- Contact form HTMLની required/email validation પછી `mailto:` draft બનાવે છે. Name, reply email, subject અને message prefill થાય છે; website પોતે send થયાનો દાવો કરતી નથી.
- Skip-to-content link, semantic landmarks, meaningful image alt, form labels, keyboard focus outline සහ `prefers-reduced-motion` support સામેલ છે.
- LeetCode tab new windowમાં ખૂલે ત્યારે `rel="noopener noreferrer"` વપરાય છે.

## Contact form: live delivery setup

હાલનું static form required/email validation પછી visitorના default email appમાં prefilled `mailto:` draft ખોલે છે; તે site મારફતે inboxમાં submit થતું નથી. વાસ્તવિક web submission માટે [CONTACT-FORM-SETUP.md](./CONTACT-FORM-SETUP.md)માં recommended Formspree setup, મોકલવાની endpoint માહિતી, test steps અને secrets અંગેની સુરક્ષા નોંધો છે. Formspree endpoint મળ્યા પછી જ તેને wire કરીને successful provider response પર success status બતાવી શકાય. Password, SMTP credential કે private API keyની જરૂર નથી કે તે માંગવી નહીં.

## Run અને preview

1. `portfolio.html`ને browserમાં ખોલો અથવા VS Code Live Serverથી serve કરો.
2. Local assets માટે `assets/` folderનું સ્થાન જાળવો.
3. Inter માટે internet ઉપલબ્ધ ન હોય તો fallback font વપરાશે.

Static hosting માટે `portfolio.html` અને `assets/` upload કરો. Host `index.html` માગે તો entry mapping અથવા copyનો ઉપયોગ કરો અને relative asset paths જાળવો.

## Content update

- **Design system:** `portfolio.html`ના `:root` CSS variablesમાં રંગ, spacing, radius અને width બદલો.
- **Hero/About photos:** હાલના `<img src>` અને meaningful `alt` text update કરો.
- **Resume:** `assets/resume/Aarjav_Resume.pdf` replace કરો અથવા navbar/mobile/hero download links સુધારો.
- **Projects:** Project cardમાં title, description, tags અને actual GitHub URL સુધારો; live demo હોય ત્યારે જ તેનો link ઉમેરો.
- **Skills:** સંબંધિત `.skill-card`ના heading અને `.skill-tag` items update કરો; subjective percentages ઉમેરશો નહીં.
- **Experience/Education:** સંબંધિત panelમાં ચકાસેલી તારીખો/માહિતી update કરો.
- **Certificates:** `#certificates`ની listમાં title, issuer, issue date, આપેલો credential ID અને matching image path update કરો; verified URL જ link કરો. Preview buttonના `data-certificate-*` attributes modal image/alt/download update કરે છે. Internship completion image `assets/certificates/`માં જાળવો.
- **Contact/social:** Email, phone, location અને existing profile URLs સંબંધિત HTMLમાં બદલો. Live form service જોડવા માટે [CONTACT-FORM-SETUP.md](./CONTACT-FORM-SETUP.md) અનુસરો.
- **Responsive changes:** `portfolio.html`ના Responsive CSS sectionમાં breakpoint/layout update કરો; પછી desktop અને mobile બંને તપાસો.

## હાલની મર્યાદાઓ અને નોંધો

- Contact form browserમાં required/email validation કરે છે અને visitorના default email appમાં prefilled draft ખોલે છે. Visitorએ email appમાંથી જાતે send કરવો પડે છે; website form દ્વારા email અથવા data store/transmit કરતી નથી. App ન ખૂલે તો સીધો email link વાપરી શકાય છે. Live website submission હજી configured નથી; endpoint અને provider setup માટે [CONTACT-FORM-SETUP.md](./CONTACT-FORM-SETUP.md) જુઓ.
- Certificatesની વિગતો user દ્વારા આપવામાં આવી છે (ઉપરની table જુઓ). Simplilearn, Credly અને Coursera માટે user-supplied verification links વપરાય છે; Hours of AI અને Green Skills and Artificial Intelligence માટે public URL આપવામાં આવ્યો નથી. LinkedInની authenticated-only માહિતીમાંથી કંઈ copy કરવાનો દાવો નથી.
- છ certificate image files તેમના corresponding records સાથે જોડાયેલા છે: `Agile_Scrum_Master.jpg`, `AWS.jpeg`, `Hour_of_AI.jpeg`, `AI_ML.jpeg`, `Java.jpeg` અને `AIT.jpeg`. દરેક card image inline બતાવે છે અને full preview/download પણ આપે છે. BrainyBeam completion certificate Experienceમાં તથા AIT Hackathon participation certificate Education highlightમાં inline/modal preview અને download સાથે છે.
- Education brief અને અગાઉના HTML વચ્ચે તફાવત હતો. હાલના HTMLની values જાળવી છે: GLS B.E. CSE `2022–2026`, 7th semester, `CGPA 8.5+`; publish પહેલાં ownerથી verify કરો.
- Footer year `2026` છે; publish સમયે જરૂરી હોય તો સુધારો.
- Counts strip હાલ પાંચ selected projects, છ skill groups, છ certificate records અને Experience & Educationમાં internship તથા hackathon highlight ગણે છે; તે કુલ career achievementsનો દાવો નથી.
