# 🧪 Weave Tutorials

Welcome to the Weave tutorials! This collection of notebooks provides a comprehensive learning path from basic concepts to advanced production applications. Each tutorial is designed to be hands-on and practical, helping you master Weave's capabilities for building, evaluating, and deploying AI applications.

## 📁 Folder Structure

```
tutorials/
├── 01-getting-started/     # Basic concepts and initial setup
├── 02-core-features/       # Essential data handling features
├── 03-advanced-applications/ # Complex workflows and advanced techniques
└── 04-production-enterprise/ # Production deployment and enterprise features
```

## 📚 Learning Path

### 1. Getting Started
Start here if you're new to Weave. These tutorials cover fundamental concepts and basic usage patterns.

### 2. Core Features & Data Handling
Learn essential features for logging, tracking, and managing data in Weave.

### 3. Advanced Applications
Explore sophisticated use cases and advanced techniques for complex AI workflows.

### 4. Production & Enterprise
Master production deployment, monitoring, and enterprise-grade features.

---

## 📖 Tutorial Descriptions

### 📁 01-getting-started/

#### [Introduction Notebook](01-getting-started/intro_notebook.ipynb)
**What you'll learn**: The foundational concepts of Weave including:
- Installing and setting up Weave
- Basic tracing with `@weave.op` decorator
- Tracking custom functions and vendor integrations (OpenAI, Anthropic, etc.)
- Working with nested function calls
- Error tracking and debugging
- Publishing and retrieving objects (Models, Datasets, SystemPrompts)
- Running your first evaluation

**Key concepts**: Tracing, Operations, Objects, Evaluation basics

#### [Intro to Weave: Hello Trace](01-getting-started/Intro_to_Weave_Hello_Trace.ipynb)
**What you'll learn**: Deep dive into Weave's tracing capabilities:
- Understanding what traces are and why they matter
- Setting up your environment with proper API keys
- Creating your first traced function with `@weave.op`
- Visualizing traces in the Weave UI
- Best practices for trace organization

**Key concepts**: Trace visualization, Function decoration, Debugging workflows

#### [Intro to Weave: Hello Eval](01-getting-started/Intro_to_Weave_Hello_Eval.ipynb)
**What you'll learn**: Building your first evaluation pipeline:
- Understanding evaluation-driven development
- Creating datasets for testing
- Writing custom scoring functions
- Running evaluations and interpreting results
- Comparing model performance across iterations

**Key concepts**: Evaluation framework, Scoring functions, Dataset management

#### [Models and Weave Integration Demo](01-getting-started/Models_and_Weave_Integration_Demo.ipynb)
**What you'll learn**: Integrating existing models with Weave:
- Converting existing code to Weave Models
- Model versioning and tracking
- Integration patterns for different model types
- Best practices for model organization

**Key concepts**: Model wrapping, Version control, Integration patterns

---

### 📁 02-core-features/

#### [Log Audio With Weave](02-core-features/audio_with_weave.ipynb)
**What you'll learn**: Handling multimedia data in Weave:
- Logging audio files and metadata
- Processing audio data with LLMs
- Creating audio-based evaluations
- Best practices for large file handling

**Key concepts**: Multimedia logging, Audio processing, File management

#### [Log Calls from Existing CSV](02-core-features/import_from_csv.ipynb)
**What you'll learn**: Importing and working with existing datasets:
- Converting CSV data to Weave datasets
- Batch processing existing data
- Data validation and cleaning
- Creating evaluation datasets from historical data

**Key concepts**: Data import, CSV processing, Batch operations

#### [Using HuggingFace Datasets in evaluations with preprocess_model_input](02-core-features/hf_dataset_evals.ipynb)
**What you'll learn**: Leveraging HuggingFace datasets:
- Loading and preprocessing HuggingFace datasets
- Custom preprocessing functions
- Integration with Weave evaluations
- Handling large-scale datasets efficiently

**Key concepts**: HuggingFace integration, Data preprocessing, Scale handling

#### [Log Feedback from Production](02-core-features/feedback_prod.ipynb)
**What you'll learn**: Capturing and utilizing production feedback:
- Setting up feedback collection systems
- Processing user feedback at scale
- Using feedback for model improvement
- Creating feedback loops in production

**Key concepts**: Feedback systems, Production monitoring, Continuous improvement

#### [Custom Model Cost](02-core-features/custom_model_cost.ipynb)
**What you'll learn**: Managing and tracking model costs:
- Custom cost calculation for different models
- Cost tracking across evaluations
- Budget management strategies
- Cost optimization techniques

**Key concepts**: Cost tracking, Budget management, Optimization

#### [Leaderboard Quickstart](02-core-features/leaderboard_quickstart.ipynb)
**What you'll learn**: Creating and managing model leaderboards:
- Setting up competitive evaluations
- Creating public/private leaderboards
- Ranking models across multiple metrics
- Sharing results with stakeholders

**Key concepts**: Leaderboards, Competition setup, Results sharing

---

### 📁 03-advanced-applications/

#### [Chain of Density Summarization](03-advanced-applications/chain_of_density.ipynb)
**What you'll learn**: Advanced text summarization techniques:
- Implementing Chain of Density (CoD) summarization
- Processing ArXiv papers and technical documents
- Creating iterative refinement pipelines
- Evaluating summarization quality with LLM-as-judge

**Key concepts**: CoD technique, Document processing, Quality evaluation

#### [Code Generation](03-advanced-applications/codegen.ipynb)
**What you'll learn**: Building code generation systems:
- Creating structured code generation pipelines
- Using OpenAI's structured outputs
- Implementing code formatting and validation
- Evaluating code quality with HumanEval
- Handling code execution safely

**Key concepts**: Code generation, Structured outputs, Code evaluation

#### [Prompt Optimization](03-advanced-applications/dspy_prompt_optimization.ipynb)
**What you'll learn**: Systematic prompt improvement:
- Using DSPy for prompt optimization
- Automated prompt engineering
- Measuring prompt effectiveness
- Iterative prompt refinement

**Key concepts**: Prompt engineering, Optimization algorithms, Performance measurement

#### [Structured Outputs for Multi-Agent Systems](03-advanced-applications/multi-agent-structured-output.ipynb)
**What you'll learn**: Building multi-agent AI systems:
- Designing structured communication protocols
- Coordinating multiple AI agents
- Handling complex multi-step workflows
- Ensuring consistency across agents

**Key concepts**: Multi-agent systems, Structured communication, Workflow orchestration

#### [OCR Pipeline](03-advanced-applications/ocr-pipeline.ipynb)
**What you'll learn**: End-to-end OCR processing:
- Building OCR pipelines with vision models
- Processing documents and images
- Extracting structured data from visual content
- Quality assurance for OCR outputs

**Key concepts**: OCR processing, Vision models, Document processing

#### [NotDiamond Custom Routing](03-advanced-applications/notdiamond_custom_routing.ipynb)
**What you'll learn**: Intelligent model routing:
- Implementing custom routing logic
- Using NotDiamond for optimal model selection
- Dynamic model switching based on inputs
- Performance optimization through routing

**Key concepts**: Model routing, Performance optimization, Dynamic selection

---

### 📁 04-production-enterprise/

#### [Integrating with Weave - Production Dashboard](04-production-enterprise/online_monitoring.ipynb)
**What you'll learn**: Production monitoring and observability:
- Setting up production dashboards
- Real-time monitoring of model performance
- Alerting and incident response
- Production debugging techniques

**Key concepts**: Production monitoring, Observability, Incident response

#### [Handling and Redacting PII](04-production-enterprise/pii.ipynb)
**What you'll learn**: Privacy and compliance in production:
- Identifying and handling PII data
- Multiple redaction strategies (regex, Presidio, Faker)
- Encryption and anonymization techniques
- Compliance considerations for sensitive data

**Key concepts**: PII handling, Privacy compliance, Data protection

#### [Scorers as Guardrails](04-production-enterprise/scorers_as_guardrails.ipynb)
**What you'll learn**: Building production safety systems:
- Creating guardrail scorers for safety checks
- Implementing content moderation
- Real-time safety validation
- Balancing safety with performance

**Key concepts**: Safety systems, Content moderation, Guardrails

#### [Service API](04-production-enterprise/weave_via_service_api.ipynb)
**What you'll learn**: Production API deployment:
- Deploying Weave as a service
- REST API design and implementation
- Authentication and authorization
- Scaling considerations

**Key concepts**: API deployment, Service architecture, Scaling

#### [Weights & Biases MCP Server](04-production-enterprise/wandb_mcp_server.ipynb)
**What you'll learn**: Advanced integration patterns:
- Setting up MCP (Model Context Protocol) servers
- Integrating Weave with external systems
- Building custom integrations
- Advanced workflow automation

**Key concepts**: MCP protocol, System integration, Automation

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Weave account (sign up at [wandb.ai](https://wandb.ai))
- API keys for services you plan to use (OpenAI, Anthropic, etc.)

### Installation
```bash
pip install weave
```

### Quick Start
1. Start with `01-getting-started/intro_notebook.ipynb`
2. Follow the notebooks in order within each folder
3. Each notebook builds on concepts from previous ones
4. Check the "Key concepts" section of each notebook for important takeaways

## 📊 Progress Tracking

Track your learning progress:

- [ ] **Getting Started**: Complete all 4 introductory notebooks
- [ ] **Core Features**: Master data handling and basic features
- [ ] **Advanced Applications**: Build complex AI workflows
- [ ] **Production**: Deploy and monitor in production

## 🔗 Additional Resources

- [Weave Documentation](https://docs.wandb.ai/weave)
- [Community Forum](https://community.wandb.ai)
- [GitHub Issues](https://github.com/wandb/weave/issues)
- [Video Tutorials](https://www.youtube.com/@WeightsBiases)

## 💡 Tips for Success

1. **Run notebooks sequentially**: Each builds on the previous
2. **Experiment freely**: Try modifying parameters and approaches
3. **Check the UI**: Use the Weave dashboard to visualize results
4. **Join the community**: Share questions and learnings
5. **Start simple**: Master basics before moving to advanced topics

---

Happy learning! 🎉
