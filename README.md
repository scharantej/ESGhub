## Flask Application Design

### HTML Files

**home.html**
- Landing page with an overview of the company's ESG initiatives.
- Contains a menu bar with links to the other four pages.

**environment.html**
- Customizable page highlighting environmental performance metrics, goals, and initiatives.
- Includes a section for uploading relevant files.

**social.html**
- Editable page showcasing social impact, including community involvement, employee well-being, and diversity and inclusion efforts.
- Allows for image or video inclusion.

**governance.html**
- Outlines governance structure, ethical principles, and risk management practices.
- Includes a section for uploading relevant documents.

**score.html**
- Displays sustainability score based on information from other pages.
- Generates recommendations for improving ESG performance.

### Routes

**@app.route('/')**
- Home page.

**@app.route('/environment')**
- Environment page.

**@app.route('/social')**
- Social page.

**@app.route('/governance')**
- Governance page.

**@app.route('/score')**
- Score and recommendations page.
- Calculates score and generates recommendations based on form data from other pages.