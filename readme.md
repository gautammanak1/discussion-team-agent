# Discussion Team Agent

![uagents](https://img.shields.io/badge/uagents-4A90E2) ![a2a](https://img.shields.io/badge/a2a-000000) ![agno](https://img.shields.io/badge/agno-FF69B4) ![innovationlab](https://img.shields.io/badge/innovationlab-3D8BD3) ![chatprotocol](https://img.shields.io/badge/chatprotocol-1D3BD4) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/gautammanak02)

## 🎯 Discussion Team Agent: Your AI-Powered Research Collaboration Partner

Need comprehensive research on any topic from multiple perspectives? The Discussion Team Agent is your AI-powered research collaboration system, designed to gather insights from diverse online platforms and synthesize them into comprehensive, well-structured analysis. Using advanced AI agents working together, this system delivers detailed research with structured tables, direct links, and balanced perspectives to give you a complete understanding of any topic.

### What it Does
This agent helps you quickly understand complex topics by gathering insights from HackerNews technical discussions, academic research papers, and Twitter trending conversations. All agents work together to provide a holistic view with detailed analysis and actionable insights.

## ✨ Key Features

* **Multi-Platform Research** - Gathers insights from HackerNews, academic databases, and Twitter/X
* **Collaborative AI Agents** - Three specialized researchers work together simultaneously
* **Structured Analysis** - Comprehensive tables, direct links, and organized findings
* **Balanced Perspectives** - Both positive and negative viewpoints with quantitative data
* **Academic Integration** - Direct links to research papers and scholarly sources
* **Real-Time Insights** - Current discussions and trending topics from social platforms

### Example Query

```plaintext
Discuss the societal impact of large language models.
```

### Expected Output Structure

```markdown
# Societal Impact of Large Language Models: Comprehensive Analysis

## Executive Summary
[2-3 paragraph overview of key findings]

## Detailed Findings by Platform



### HackerNews Technical Analysis  
[Technical insights with summary table]
| Post Title | Points | Comments | Technical Focus | Industry Impact | Key Insight |
|------------|--------|----------|-----------------|-----------------|-------------|

### Academic Research Analysis
[Research findings with summary table]
| Paper Title | Authors | Publication | Year | Citations | Key Finding | Direct Link |
|-------------|---------|-------------|------|-----------|-------------|-------------|

### Twitter/X Trending Analysis
[Social media insights with summary table]
| Username | Followers | Tweet Content | Engagement | Sentiment | Key Point | Direct Link |
|----------|-----------|---------------|------------|-----------|-----------|-------------|

## Cross-Platform Analysis
[Comparison and synthesis tables]

## Impact Assessment
[Positive/Negative impacts in table format]

## Recommendations
[Actionable insights and strategies]

## Conclusion
[Summary of key takeaways]
```

## 🧠 Agent Team Composition



### 1. HackerNews Researcher  
- **Focus**: Technical discussions and industry insights
- **Tools**: HackerNews API integration
- **Output**: Technical deep-dives, industry implications, expert opinions
- **Mandatory**: Summary table with direct links to HN posts

### 2. Academic Paper Researcher
- **Focus**: Scholarly research and academic literature
- **Tools**: Google Search + Arxiv tools
- **Output**: Research papers, methodology analysis, citation data
- **Mandatory**: Summary table with direct links to PDFs/papers

### 3. Twitter Researcher
- **Focus**: Real-time trends and social media discussions
- **Tools**: DuckDuckGo search for Twitter content
- **Output**: Trending topics, influencer perspectives, viral discussions
- **Mandatory**: Summary table with direct links to tweets

## 🚀 Getting Started

### Prerequisites
- Python 3.11+
- Google API key for Gemini AI models
- Internet connection for web scraping and API access

### Installation

1. **Clone the repository**
```bash
git clone <repository-url>
cd collaboration_team
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Set up environment variables**
Create a `.env` file with:
```env
GOOGLE_API_KEY=your_google_api_key_here
```

4. **Run the agent**
```bash
python main.py
```

### Docker Setup

1. **Build and run with Docker Compose**
```bash
docker-compose up --build
```

2. **Or build manually**
```bash
docker build -t discussion-team-agent .
docker run -p 8033:8033 --env-file .env discussion-team-agent
```

## 📊 Usage Examples

### Basic Research Query
```
"Discuss the future of renewable energy"
```

### Specific Topic Analysis
```
"Analyze the impact of social media on mental health"
```

### Industry Research
```
"Research the competitive landscape of electric vehicles"
```

### Academic Topic Exploration
```
"Explore recent developments in quantum computing"
```

## 🔧 Technical Architecture

- **Framework**: uAgents + A2A Protocol + Agno Framework
- **AI Models**: Google Gemini 2.0 Flash
- **Communication**: Asynchronous agent collaboration
- **Data Sources**: Multi-platform web scraping and API integration
- **Output Format**: Markdown with tables, links, and structured analysis

## 📋 Required Dependencies

The agent requires the following key packages:
- `uagents==0.22.7` - Agent framework
- `agno` - AI agent collaboration
- `a2a-sdk` - Protocol implementation
- `google-generativeai` - Gemini AI integration
- `httpx`, `fastapi`, `uvicorn` - Web server components

## 🌐 API Endpoints

- **Port 8033**: Main agent server
- **Port 10020**: A2A protocol communication
- **Port 9999**: Additional services

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Bug fixes
- Feature enhancements
- Documentation improvements
- Performance optimizations

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Gautam Manak**  
🔗 [Portfolio](https://gautammanak.vercel.app/)

## 🌐 Socials

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_half_engineer_01) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/gautammanak1) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@gautammanak1) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/user:21267046) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/gautammanak02) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@gautammanakbtech) [![Codepen](https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white)](https://codepen.io/gautammanak1)

## 🧠 Inspired by

* [Fetch.ai uAgents](https://github.com/fetchai/uAgents)
* [Agno Framework](https://github.com/agno-agi/agno)
* [A2A Protocol](https://a2a-protocol.org/latest/)
* [Fetch.ai Innovation Lab Examples](https://github.com/fetchai/innovation-lab-examples)

## 🆘 Troubleshooting

### Common Issues

1. **API Key Errors**: Ensure your Google API key is correctly set in the `.env` file
2. **Port Conflicts**: Check if ports 8033, 10020, or 9999 are already in use
3. **Dependency Issues**: Run `pip install -r requirements.txt` to ensure all packages are installed
4. **Docker Issues**: Use `docker-compose down` and `docker-compose up --build` to rebuild

### Performance Tips

- The agent works best with specific, focused queries
- Complex topics may take longer to research (up to 10 minutes)
- Ensure stable internet connection for optimal performance

## 📈 Future Enhancements

- [ ] Additional research platforms (LinkedIn, Medium, etc.)
- [ ] Enhanced table generation and formatting
- [ ] Export functionality (PDF, Word, Excel)
- [ ] Custom research templates
- [ ] Multi-language support
- [ ] Advanced filtering and search options


