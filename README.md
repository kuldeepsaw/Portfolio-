# Portfolio-
export default function Portfolio() { return ( <div className="min-h-screen bg-[#f7f3ee] text-[#3d2c1f] font-sans"> {/* Hero Section */} <section className="max-w-6xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center"> <div className="space-y-6"> <p className="uppercase tracking-[0.3em] text-sm text-[#8b6b52]"> Educational Video Editor </p>

<h1 className="text-6xl md:text-7xl font-serif leading-tight">
        Kuldeep Saw
      </h1>

      <p className="text-lg text-[#5b4635] leading-relaxed max-w-xl">
        I create clean, aesthetic and engaging educational videos that
        make learning simple, professional and impactful.
      </p>

      <div className="flex flex-wrap gap-4 pt-2">
        <button className="px-6 py-3 rounded-2xl bg-[#3d2c1f] text-white shadow-lg hover:scale-105 transition">
          View Portfolio
        </button>

        <button className="px-6 py-3 rounded-2xl border border-[#3d2c1f] hover:bg-[#ebe3d9] transition">
          Contact Me
        </button>
      </div>
    </div>

    <div className="flex justify-center">
      <div className="bg-white p-4 rounded-[2rem] shadow-2xl w-[320px]">
        <img
          src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1200&auto=format&fit=crop"
          alt="editor setup"
          className="rounded-[1.5rem] object-cover h-[450px] w-full"
        />
      </div>
    </div>
  </section>

  {/* About */}
  <section className="max-w-6xl mx-auto px-6 py-10">
    <div className="bg-white rounded-[2rem] p-8 md:p-12 shadow-lg grid md:grid-cols-2 gap-10">
      <div>
        <h2 className="text-4xl font-serif mb-6">About Me</h2>
        <p className="text-[#5b4635] leading-relaxed text-lg">
          I am a passionate video editor focused on educational content,
          lecture editing, explainer videos and YouTube educational
          projects. My goal is to create videos that keep viewers engaged
          while delivering information clearly.
        </p>
      </div>

      <div>
        <h2 className="text-4xl font-serif mb-6">What I Do</h2>
        <ul className="space-y-4 text-lg text-[#5b4635]">
          <li>• Educational Video Editing</li>
          <li>• Lecture Editing</li>
          <li>• YouTube Educational Content</li>
          <li>• Explainer Video Editing</li>
          <li>• Clean Motion & Transitions</li>
        </ul>
      </div>
    </div>
  </section>

  {/* Skills */}
  <section className="max-w-6xl mx-auto px-6 py-10">
    <h2 className="text-4xl font-serif text-center mb-12">Skills</h2>

    <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
      {[
        "Clean Cuts",
        "Smooth Transitions",
        "Text & Titles",
        "Color Correction",
        "Audio Enhancement",
        "Pacing & Flow",
        "Content Structuring",
        "Professional Editing",
      ].map((skill) => (
        <div
          key={skill}
          className="bg-white rounded-3xl p-6 shadow-md hover:-translate-y-2 transition"
        >
          <p className="font-medium text-center">{skill}</p>
        </div>
      ))}
    </div>
  </section>

  {/* Tools */}
  <section className="max-w-6xl mx-auto px-6 py-10">
    <div className="bg-[#ebe3d9] rounded-[2rem] p-10">
      <h2 className="text-4xl font-serif text-center mb-10">
        Tools I Use
      </h2>

      <div className="grid md:grid-cols-3 gap-8">
        {[
          {
            name: 'CapCut',
            desc: 'Professional mobile editing',
          },
          {
            name: 'VN Editor',
            desc: 'Smooth timeline editing',
          },
          {
            name: 'Canva',
            desc: 'Creative thumbnails & graphics',
          },
        ].map((tool) => (
          <div
            key={tool.name}
            className="bg-white rounded-3xl p-8 text-center shadow-md"
          >
            <h3 className="text-2xl font-semibold mb-3">{tool.name}</h3>
            <p className="text-[#5b4635]">{tool.desc}</p>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Quote */}
  <section className="max-w-4xl mx-auto px-6 py-10 text-center">
    <div className="bg-white rounded-[2rem] p-10 shadow-lg">
      <p className="text-3xl italic font-serif leading-relaxed text-[#5b4635]">
        “Good editing makes the content clear, the message strong and the
        impact lasting.”
      </p>
    </div>
  </section>

  {/* Contact */}
  <section className="max-w-6xl mx-auto px-6 py-16">
    <div className="bg-[#3d2c1f] text-white rounded-[2rem] p-10 md:p-14 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h2 className="text-5xl font-serif mb-6">Contact</h2>
        <div className="space-y-4 text-lg">
          <p>📞 7004754904</p>
          <p>✉ ksawboard@gmail.com</p>
        </div>
      </div>

      <div className="text-right">
        <p className="text-2xl italic text-[#d8c4b0]">
          Let’s create meaningful educational content together.
        </p>
      </div>
    </div>
  </section>
</div>

); }
