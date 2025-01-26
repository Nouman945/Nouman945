import React from 'react';
import { Github, Linkedin, Mail, Instagram } from 'lucide-react';

const GitHubProfile = () => {
  return (
    <div className="max-w-4xl mx-auto p-8 bg-gray-900 text-gray-100">
      {/* Header Section */}
      <header className="text-center mb-12">
        <h1 className="text-3xl font-bold mb-4">👋 Hi there, I'm Nouman Rasheed</h1>
        <div className="h-16 flex items-center justify-center bg-gray-800 rounded-lg">
          {/* Placeholder for the typing animation */}
          <p className="text-green-400 text-xl">Development | Research | Computer Vision | Gen AI | NLP</p>
        </div>
      </header>

      {/* About Section */}
      <section className="mb-12">
        <h2 className="text-2xl font-bold mb-6 flex items-center">
          <span className="mr-2">🚀</span> About Me
        </h2>
        <div className="bg-gray-800 rounded-lg p-6 mb-6">
          <p className="text-lg mb-4">
            I'm a passionate technologist dedicated to pushing the boundaries of what's possible in AI and software development.
          </p>
          <pre className="bg-gray-700 p-4 rounded-lg overflow-x-auto">
            <code className="text-sm">
{`tech_focus = {
    "AI & ML": {
        "areas": ["Computer Vision", "Generative AI", "NLP"],
        "status": "Actively researching and implementing"
    },
    "Backend": {
        "frameworks": ["Flask", "Django"],
        "expertise": "RESTful APIs and System Architecture"
    },
    "DevOps": {
        "tools": ["Docker", "CI/CD", "Cloud"],
        "goal": "Building scalable, reliable systems"
    }
}`}
            </code>
          </pre>
        </div>
      </section>

      {/* GitHub Stats Section */}
      <section className="mb-12">
        <h2 className="text-2xl font-bold mb-6 flex items-center">
          <span className="mr-2">📊</span> GitHub Statistics
        </h2>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div className="bg-gray-800 rounded-lg p-4">
            <img 
              src="/api/placeholder/400/200"
              alt="GitHub Stats"
              className="w-full h-48 object-cover rounded"
            />
          </div>
          <div className="bg-gray-800 rounded-lg p-4">
            <img 
              src="/api/placeholder/400/200"
              alt="GitHub Streak"
              className="w-full h-48 object-cover rounded"
            />
          </div>
        </div>
      </section>

      {/* Technical Expertise Section */}
      <section className="mb-12">
        <h2 className="text-2xl font-bold mb-6 flex items-center">
          <span className="mr-2">🛠️</span> Technical Expertise
        </h2>
        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
          {/* Core Technologies */}
          <div className="bg-gray-800 rounded-lg p-6">
            <h3 className="text-xl font-semibold mb-4">Core Technologies</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-blue-600 rounded-full text-sm">Python</span>
              <span className="px-3 py-1 bg-yellow-500 rounded-full text-sm">JavaScript</span>
              <span className="px-3 py-1 bg-blue-500 rounded-full text-sm">C++</span>
            </div>
          </div>

          {/* AI & ML */}
          <div className="bg-gray-800 rounded-lg p-6">
            <h3 className="text-xl font-semibold mb-4">AI & Machine Learning</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-orange-500 rounded-full text-sm">TensorFlow</span>
              <span className="px-3 py-1 bg-red-500 rounded-full text-sm">PyTorch</span>
              <span className="px-3 py-1 bg-orange-400 rounded-full text-sm">scikit-learn</span>
            </div>
          </div>

          {/* Web Development */}
          <div className="bg-gray-800 rounded-lg p-6">
            <h3 className="text-xl font-semibold mb-4">Web Development</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-blue-400 rounded-full text-sm">React</span>
              <span className="px-3 py-1 bg-green-700 rounded-full text-sm">Django</span>
              <span className="px-3 py-1 bg-gray-700 rounded-full text-sm">Flask</span>
            </div>
          </div>
        </div>
      </section>

      {/* Connect Section */}
      <section className="text-center">
        <h2 className="text-2xl font-bold mb-6 flex items-center justify-center">
          <span className="mr-2">🤝</span> Connect With Me
        </h2>
        <div className="flex justify-center space-x-4">
          <a href="mailto:muhmmadnouman945@gmail.com" className="p-2 bg-gray-800 rounded-lg hover:bg-gray-700">
            <Mail className="w-6 h-6" />
          </a>
          <a href="https://www.linkedin.com/in/nouman-rasheed-5a003b157" className="p-2 bg-gray-800 rounded-lg hover:bg-gray-700">
            <Linkedin className="w-6 h-6" />
          </a>
          <a href="https://www.instagram.com/_nouman_r" className="p-2 bg-gray-800 rounded-lg hover:bg-gray-700">
            <Instagram className="w-6 h-6" />
          </a>
          <a href="https://github.com/Nouman945" className="p-2 bg-gray-800 rounded-lg hover:bg-gray-700">
            <Github className="w-6 h-6" />
          </a>
        </div>
      </section>

      {/* Footer */}
      <footer className="mt-12 text-center text-gray-400">
        <div className="mb-4">
          <img 
            src="/api/placeholder/150/30"
            alt="Profile Views Counter"
            className="mx-auto"
          />
        </div>
        <p className="italic">Thanks for visiting! Feel free to ⭐ repositories you find interesting.</p>
      </footer>
    </div>
  );
};

export default GitHubProfile;
