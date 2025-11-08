# LRK007..
export default function LailaPortfolio() { 
return ( 
 <div className="min-h-screen bg-white text-slate-800 antialiased"> 
   <header className="bg-gradient-to-r from-slate-50 to-white shadow-sm"> 
     <div className="max-w-5xl mx-auto px-6 py-6 flex items-center justify-between"> 
       <div> 
         <h1 className="text-2xl font-semibold">Laila R K— Metallurgical Engineer (BE)</h1>
         <p className="text-sm text-slate-500">Government College of Engineering, Salem-11</p>
       </div> <nav className="space-x-4 text-sm text-slate-600">
         <a href="#about" className="hover:underline">About</a>
         <a href="#education" className="hover:underline">Education</a> 
         <a href="#skills" className="hover:underline">Skills</a> 
         <a href="#projects" className="hover:underline">Projects</a>
         <a href="#achievements" className="hover:underline">Achievements</a> 
         <a href="#contact" className="hover:underline">Contact</a> </nav> </div> </header>

<main className="max-w-5xl mx-auto px-6 py-12">
    {/* Hero */}
    <section id="hero" className="grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h2 className="text-4xl md:text-5xl font-extrabold leading-tight">Laila R K</h2>
        <p className="mt-3 text-lg text-slate-600">Metallurgical Engineer in the making — passionate about materials, microstructures and sustainable material processing.</p>

        <div className="mt-6 flex items-center gap-3">
          <a href="#projects" className="inline-block px-5 py-3 bg-slate-800 text-white rounded-lg shadow">View Projects</a>
          <a href="#contact" className="inline-block px-4 py-3 border border-slate-200 rounded-lg text-slate-700">Contact</a>
        </div>

        <ul className="mt-6 text-sm text-slate-500 space-y-2">
          <li><strong>College:</strong> Government College of Engineering, Salem-11</li>
          <li><strong>Email:</strong> lailarameshrk@gmail.com</li>
          <li><strong>Focus:</strong> Metallography, heat treatment, corrosion, materials characterization</li>
        </ul>
      </div>

      <div className="p-6 bg-slate-50 rounded-2xl shadow-sm">
        <h3 className="text-lg font-semibold">Academic Snapshot</h3>
        <div className="mt-4 grid grid-cols-2 gap-4">
          <div className="p-4 bg-white rounded-lg border border-slate-100">
            <p className="text-xs text-slate-400">Degree</p>
            <p className="font-medium">B.E. Metallurgical Engineering</p>
          </div>
          <div className="p-4 bg-white rounded-lg border border-slate-100">
            <p className="text-xs text-slate-400">College</p>
            <p className="font-medium">Government College of Engineering, Salem-11</p>
          </div>
          <div className="p-4 bg-white rounded-lg border border-slate-100">
            <p className="text-xs text-slate-400">Graduation</p>
            <p className="font-medium">Expected: [Year]</p>
          </div>
          <div className="p-4 bg-white rounded-lg border border-slate-100">
            <p className="text-xs text-slate-400">GPA / Percent</p>
            <p className="font-medium">[Add your CGPA or %]</p>
          </div>
        </div>
      </div>
    </section>

    {/* About */}
    <section id="about" className="mt-12">
      <h3 className="text-2xl font-semibold">About Me</h3>
      <p className="mt-3 text-slate-600">I am pursuing a Bachelor of Engineering in Metallurgy at Government College of Engineering, Salem-11. My academic work centers on microstructural analysis, heat treatment processes, corrosion behaviour, and materials selection for industrial applications. I enjoy hands-on laboratory work, data-driven analysis, and translating metallurgical principles into practical solutions.</p>
    </section>

    {/* Education */}
    <section id="education" className="mt-10">
      <h3 className="text-2xl font-semibold">Education</h3>

      <div className="mt-6 grid md:grid-cols-2 gap-6">
        <div className="p-6 bg-white rounded-xl border border-slate-100 shadow-sm">
          <h4 className="font-semibold">B.E. Metallurgical Engineering</h4>
          <p className="text-sm text-slate-500">Government College of Engineering, Salem-11</p>
          <p className="mt-3 text-slate-600">Relevant coursework: Physical Metallurgy, Thermodynamics of Materials, Phase Transformations, Corrosion Engineering, Materials Characterization (SEM/XRD basics), Heat Treatment and Mechanical Testing.</p>
        </div>

        <div className="p-6 bg-white rounded-xl border border-slate-100 shadow-sm">
          <h4 className="font-semibold">Additional Training & Workshops</h4>
          <ul className="mt-3 text-slate-600 list-disc list-inside space-y-2 text-sm">
            <li>Workshop on Metallography and Specimen Preparation — [Institute / Year]</li>
            <li>Seminar on Corrosion Prevention Techniques — [Event / Year]</li>
            <li>Hands-on training: Universal Testing Machine, Hardness Testing — [Lab / Year]</li>
          </ul>
        </div>
      </div>
    </section>

    {/* Skills */}
    <section id="skills" className="mt-10">
      <h3 className="text-2xl font-semibold">Technical Skills</h3>
      <div className="mt-4 grid sm:grid-cols-2 md:grid-cols-4 gap-4">
        {[
          "Metallography & Microstructure Analysis",
          "Heat Treatment & Phase Transformations",
          "Mechanical Testing (UTM, Hardness)",
          "Corrosion Testing & Prevention",
          "SEM / Optical Microscopy (Basics)",
          "XRD — Basics",
          "Non-Destructive Testing (NDT) Basics",
          "Data analysis (Excel, Origin, MATLAB)"
        ].map((s) => (
          <div key={s} className="p-3 bg-white rounded-lg border border-slate-100 text-sm">{s}</div>
        ))}
      </div>
    </section>

    {/* Projects */}
    <section id="projects" className="mt-10">
      <h3 className="text-2xl font-semibold">Academic Projects</h3>

      <div className="mt-6 space-y-4">
        <article className="p-6 bg-white rounded-xl border border-slate-100 shadow-sm">
          <h4 className="font-semibold">Study of Mechanical Properties of Heat-Treated Steel</h4>
          <p className="text-sm text-slate-500">Role: Lead investigator | Tools: Optical microscope, UTM, Hardness tester</p>
          <p className="mt-3 text-slate-600">Investigated how varying quenching media (water, oil, molten salt) and tempering temperature affected hardness and tensile strength. Performed microstructural analysis and correlated phases with mechanical properties. (Add data, graphs, and conclusions here.)</p>
        </article>

        <article className="p-6 bg-white rounded-xl border border-slate-100 shadow-sm">
          <h4 className="font-semibold">Corrosion Behaviour of Mild Steel in Different Environments</h4>
          <p className="text-sm text-slate-500">Role: Team member | Tools: Weight loss method, salt spray test</p>
          <p className="mt-3 text-slate-600">Studied corrosion rates in acidic, neutral and saline media, and evaluated protective coatings. (Add images, tables and brief results.)</p>
        </article>

        <article className="p-6 bg-white rounded-xl border border-slate-100 shadow-sm">
          <h4 className="font-semibold">[Your Project Title Here]</h4>
          <p className="text-sm text-slate-500">Role: [Your role] | Tools: [Tools used]</p>
          <p className="mt-3 text-slate-600">Brief description of aims, methods and outcomes. Include link to report or GitHub if available.</p>
        </article>

      </div>
    </section>

    {/* Achievements */}
    <section id="achievements" className="mt-10">
      <h3 className="text-2xl font-semibold">Achievements & Presentations</h3>
      <ul className="mt-4 list-disc list-inside text-slate-600 space-y-2">
        <li>Presented a paper on "[Title]" at [Conference / Symposium, Year].</li>
        <li>Secured [Prize/Rank] in [Event or Competition].</li>
        <li>Volunteer / member of [Student Chapter or Society].</li>
      </ul>
    </section>

    {/* Contact */}
    <section id="contact" className="mt-10 mb-16">
      <h3 className="text-2xl font-semibold">Contact</h3>
      <p className="mt-3 text-slate-600">I welcome academic collaborations, internship opportunities, and research discussions. You can reach me at:</p>

      <div className="mt-4 p-6 bg-slate-50 rounded-xl border border-slate-100 w-full max-w-xl">
        <p className="text-sm"><strong>Email:</strong> <a className="text-slate-700 underline" href="mailto:lailarameshrk@gmail.com">lailarameshrk@gmail.com</a></p>
        <p className="mt-2 text-sm"><strong>Location:</strong> Salem, Tamil Nadu</p>
        <p className="mt-2 text-sm">LinkedIn: <span className="text-slate-500">[Add your LinkedIn URL]</span></p>
      </div>

    </section>

  </main>

  <footer className="bg-white border-t border-slate-100">
    <div className="max-w-5xl mx-auto px-6 py-6 text-sm text-slate-500 text-center">© {new Date().getFullYear()} Laila R — Government College of Engineering, Salem-11</div>
  </footer>
</div>

); }
