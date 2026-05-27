export default function InteractiveCV() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">
      {/* Hero Section */}
      <section className="flex flex-col items-center justify-center text-center py-20 px-6">
        <img
          src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?q=80&w=400"
          alt="Profile"
          className="w-36 h-36 rounded-full border-4 border-white shadow-2xl mb-6 object-cover"
        />

        <h1 className="text-5xl font-bold mb-3">Joseph</h1>
        <p className="text-xl text-gray-300 mb-6">
          Electrical Engineering Student | AI Enthusiast | Developer
        </p>

        <div className="flex gap-4 flex-wrap justify-center">
          <a
            href="https://github.com/yourusername"
            target="_blank"
            className="bg-white text-black px-5 py-3 rounded-2xl font-semibold hover:scale-105 transition"
          >
            GitHub
          </a>

          <a
            href="https://linkedin.com"
            target="_blank"
            className="border border-white px-5 py-3 rounded-2xl hover:bg-white hover:text-black transition"
          >
            LinkedIn
          </a>
        </div>
      </section>

      {/* About */}
      <section className="max-w-5xl mx-auto px-6 py-12">
        <div className="bg-zinc-900 rounded-3xl p-8 shadow-xl">
          <h2 className="text-3xl font-bold mb-4">About Me</h2>

          <p className="text-gray-300 leading-8 text-lg">
            I am an enthusiastic Electrical Engineering student passionate
            about artificial intelligence, embedded systems, game development,
            and software engineering. I enjoy creating innovative projects such
            as body detection systems, AI-based games, and machine learning
            applications.
          </p>
        </div>
      </section>

      {/* Skills */}
      <section className="max-w-5xl mx-auto px-6 py-12">
        <h2 className="text-3xl font-bold mb-8 text-center">Skills</h2>

        <div className="grid md:grid-cols-3 gap-6">
          {[
            "Python",
            "Arduino",
            "Machine Learning",
            "C++",
            "HTML & CSS",
            "Computer Vision",
          ].map((skill) => (
            <div
              key={skill}
              className="bg-zinc-900 rounded-2xl p-6 text-center text-lg font-semibold hover:scale-105 transition shadow-lg"
            >
              {skill}
            </div>
          ))}
        </div>
      </section>

      {/* Projects */}
      <section className="max-w-5xl mx-auto px-6 py-12">
        <h2 className="text-3xl font-bold mb-8 text-center">Projects</h2>

        <div className="grid md:grid-cols-2 gap-8">
          <div className="bg-zinc-900 p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition">
            <h3 className="text-2xl font-bold mb-3">
              AI Boxing Detection Game
            </h3>

            <p className="text-gray-300 leading-7">
              A boxing game using body tracking and computer vision technology
              to detect player movements in real-time.
            </p>
          </div>

          <div className="bg-zinc-900 p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition">
            <h3 className="text-2xl font-bold mb-3">
              Hand Gesture Recognition
            </h3>

            <p className="text-gray-300 leading-7">
              A machine learning project capable of recognizing hand gestures
              using a webcam and AI classification.
            </p>
          </div>
        </div>
      </section>

      {/* Education */}
      <section className="max-w-5xl mx-auto px-6 py-12">
        <div className="bg-zinc-900 rounded-3xl p-8 shadow-xl">
          <h2 className="text-3xl font-bold mb-4">Education</h2>

          <p className="text-xl text-gray-300">
            Bachelor of Electrical Engineering
          </p>

          <p className="text-gray-400 mt-2">
            University Name • 2023 - Present
          </p>
        </div>
      </section>

      {/* Contact */}
      <section className="max-w-5xl mx-auto px-6 py-12 pb-20">
        <div className="bg-white text-black rounded-3xl p-10 text-center shadow-2xl">
          <h2 className="text-4xl font-bold mb-4">Contact Me</h2>

          <p className="text-lg mb-6">
            Interested in collaboration, projects, or internships?
          </p>

          <a
            href="mailto:yourmail@email.com"
            className="bg-black text-white px-6 py-4 rounded-2xl inline-block font-semibold hover:scale-105 transition"
          >
            Send Email
          </a>
        </div>
      </section>
    </div>
  );
}
# mathluv.github.io
