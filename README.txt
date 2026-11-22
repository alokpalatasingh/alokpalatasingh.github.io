HOW TO UPDATE YOUR WEBSITE (alokpalatasingh.github.io)
=====================================================

EDIT ON GITHUB
1. Go to github.com -> repository alokpalatasingh.github.io
2. Click index.html -> pencil icon (Edit)
3. Press Ctrl+F and search:  EDIT YOUR DETAILS HERE
   Everything on the site comes from that block.
4. Make your change, then click "Commit changes" (twice).
5. Wait 1-2 minutes, open the site and press Ctrl+Shift+R.

GOLDEN RULES
- Change only the text inside quotes "..."
- Keep every comma , quote " and bracket { } [ ]
- Don't type a " inside your text. Use ' instead.
- To add something: copy a similar line, paste it below, change the text.
- If the site looks blank or broken: index.html -> History -> open the
  previous version and copy it back.

ADD A PHOTO
1. Resize it (squoosh.app), name it simply: nccs-poster.jpg (lowercase, no spaces)
2. GitHub -> open the "images" folder -> Add file -> Upload files -> Commit
3. In index.html, under gallery: add a line
   {album:"Conference", caption:"Your caption", img:"images/nccs-poster.jpg", pos:"50% 30%"},
   A new album name (e.g. "IIT Madras") makes a new folder automatically.
   pos moves the crop: "50% 20%" shows more of the top.

ADD A PUBLICATION (under publications:)
   {year:2027, title:"Paper title", authors:"A. Author, <u>Alok Palatasingh</u>, B. Author", venue:"Journal, vol(issue), pages", links:[["Read the paper","https://doi.org/..."]]},
   <u>...</u> makes your name bold.

ADD A RESEARCH PROJECT (under research:)
   {status:"Ongoing", when:"Place · 2027 – present", title:"Project title", text:"Description.", tags:["Tag 1","Tag 2"]},
   Optional: team:"Supervisor: Dr. Name",

ADD AN AWARD / EXPERIENCE / CERTIFICATE
   awards:   ["2027","Award name"],
   service:  ["2027","Role, organisation"],
   certificates: {title:"Name", by:"Organiser", date:"2027", link:"", img:""},

ADD A VIDEO (the Talks tab appears automatically)
   videos:   {title:"Talk title", where:"Event", dur:"12:30", url:"https://youtu.be/...", img:""},

START YOUR PHD
   In education:, change  ["Loading…","PhD", ...]
   to  ["2027 – present","PhD, Your Field","University · Advisor: Dr. Name"]
   Also update role: (lines under your name) and facts: (Now / Next step).

CHAT ANSWERS (Ask about Alok)
   Under ask: add  ["keyword1, keyword2", "The answer."],
   Most answers update by themselves from your details.

CHANGE YOUR PORTRAIT
   Upload a new images/portrait.jpg (square, face centred). The star face updates by itself.
