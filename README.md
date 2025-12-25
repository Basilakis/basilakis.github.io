# 🚀 Material Kai Vision Platform Documentation

Welcome to the Material Kai Vision Platform documentation site!

## 📖 View Documentation

**[📚 Browse Full Documentation](https://basilakis.github.io/)**

## 🔗 Quick Links

- **[📡 API Documentation](https://v1api.materialshub.gr/docs)** - Interactive Swagger API documentation (113 endpoints)
- **[📋 ReDoc API](https://v1api.materialshub.gr/redoc)** - Alternative API documentation format

## 📊 Platform Stats

- **39** Comprehensive Documentation Files
- **120+** API Endpoints across **15** categories
- **14** AI Models (Claude Sonnet 4.5, Haiku 4.5, GPT-5, Llama 4 Scout 17B Vision, CLIP, etc.)
- **6** Embedding Types (text, visual, color, texture, application, multimodal)
- **14-Stage** PDF Processing Pipeline with checkpoint recovery and real-time monitoring
- **Complete Quote System** with status tags, upsells/extras, and project timeline tracking
- **Real-time Monitoring** with Supabase subscriptions and comprehensive analytics
- **5,000+** Active Users
- **99.5%+** Uptime

## 📋 Available Documentation

- [INDEX](https://basilakis.github.io/INDEX.html)
- [README](https://basilakis.github.io/README.html)
- [Agent System](https://basilakis.github.io/agent-system.html)
- [Ai Models Architecture](https://basilakis.github.io/ai-models-architecture.html)
- [Ai Models Guide](https://basilakis.github.io/ai-models-guide.html)
- [Api Configuration Examples](https://basilakis.github.io/api-configuration-examples.html)
- [Api Docs](https://basilakis.github.io/api-docs.html)
- [Api Endpoints](https://basilakis.github.io/api-endpoints.html)
- [Async Processing And Limits](https://basilakis.github.io/async-processing-and-limits.html)
- [Campaign System](https://basilakis.github.io/campaign-system.html)
- [Collaborative Filtering Recommendations](https://basilakis.github.io/collaborative-filtering-recommendations.html)
- [Comprehensive Metadata Fields Guide](https://basilakis.github.io/comprehensive-metadata-fields-guide.html)
- [Data Import System](https://basilakis.github.io/data-import-system.html)
- [Deployment Guide](https://basilakis.github.io/deployment-guide.html)
- [Duplicate Detection Merging](https://basilakis.github.io/duplicate-detection-merging.html)
- [Email System](https://basilakis.github.io/email-system.html)
- [Embedding Generation Improvements](https://basilakis.github.io/embedding-generation-improvements.html)
- [Extract Categories Guide](https://basilakis.github.io/extract-categories-guide.html)
- [Features Guide](https://basilakis.github.io/features-guide.html)
- [Image Relevancy And Search](https://basilakis.github.io/image-relevancy-and-search.html)
- [Intelligent Page Type Detection](https://basilakis.github.io/intelligent-page-type-detection.html)
- [Interior Design Data Flow](https://basilakis.github.io/interior-design-data-flow.html)
- [Interior Design Models](https://basilakis.github.io/interior-design-models.html)
- [Interior Designer Agent User Guide](https://basilakis.github.io/interior-designer-agent-user-guide.html)
- [Job Queue System](https://basilakis.github.io/job-queue-system.html)
- [Knowledge Base Implementation](https://basilakis.github.io/knowledge-base-implementation.html)
- [Logger Service](https://basilakis.github.io/logger-service.html)
- [Meta Field Aggregation](https://basilakis.github.io/meta-field-aggregation.html)
- [Metadata Management System](https://basilakis.github.io/metadata-management-system.html)
- [Metadata Prototype Validation System](https://basilakis.github.io/metadata-prototype-validation-system.html)
- [Metafield Extraction Guide](https://basilakis.github.io/metafield-extraction-guide.html)
- [Modular Pipeline Endpoints](https://basilakis.github.io/modular-pipeline-endpoints.html)
- [Monitoring Analytics System](https://basilakis.github.io/monitoring-analytics-system.html)
- [Monitoring And Alerting](https://basilakis.github.io/monitoring-and-alerting.html)
- [Multi Source Meta Extraction Plan](https://basilakis.github.io/multi-source-meta-extraction-plan.html)
- [Overview](https://basilakis.github.io/overview.html)
- [Pdf Processing Pipeline](https://basilakis.github.io/pdf-processing-pipeline.html)
- [Platform Flows](https://basilakis.github.io/platform-flows.html)
- [Product Discovery Architecture](https://basilakis.github.io/product-discovery-architecture.html)
- [Prompt Based Extraction Architecture](https://basilakis.github.io/prompt-based-extraction-architecture.html)
- [Prompt Enhancement System](https://basilakis.github.io/prompt-enhancement-system.html)
- [Quotes System Architecture](https://basilakis.github.io/quotes-system-architecture.html)
- [Relevancy System](https://basilakis.github.io/relevancy-system.html)
- [Saved Searches Deduplication](https://basilakis.github.io/saved-searches-deduplication.html)
- [Scraping Job Integration](https://basilakis.github.io/scraping-job-integration.html)
- [Scraping Workflow Guide](https://basilakis.github.io/scraping-workflow-guide.html)
- [Search Strategies](https://basilakis.github.io/search-strategies.html)
- [Search Suggestions](https://basilakis.github.io/search-suggestions.html)
- [Spaceformer_architecture](https://basilakis.github.io/spaceformer_architecture.html)
- [Supabase Types Automation](https://basilakis.github.io/supabase-types-automation.html)
- [System Architecture](https://basilakis.github.io/system-architecture.html)
- [Troubleshooting Guide](https://basilakis.github.io/troubleshooting-guide.html)
- [Unified Job Tracking](https://basilakis.github.io/unified-job-tracking.html)
- [Unified Product Generation Flow](https://basilakis.github.io/unified-product-generation-flow.html)
- [Web Scraping Integration](https://basilakis.github.io/web-scraping-integration.html)
- [Xml Import Orchestrator](https://basilakis.github.io/xml-import-orchestrator.html)

---

## 🏗️ Architecture

- **Frontend**: React + TypeScript + Vite (Vercel)
- **Backend**: FastAPI + Python 3.11 (Docker)
- **Database**: Supabase PostgreSQL with pgvector
- **AI Services**: OpenAI, Anthropic, Together AI, Replicate
- **Vector Search**: OpenAI embeddings (1536D), CLIP (512D)

## 🚀 Key Features

### 📄 PDF Processing & AI Pipeline
- **14-Stage AI Pipeline**: Complete PDF processing with checkpoint recovery and async job queuing
- **Real-time Monitoring**: Live progress tracking with Supabase subscriptions and comprehensive metrics
- **Product Discovery**: AI-powered dynamic product identification with metadata extraction
- **Document Entities**: Certificates, logos, specifications as separate knowledge base
- **Stage-by-Stage Tracking**: Detailed monitoring for all 14 stages (INITIALIZED → COMPLETED)
- **Error Recovery**: Automatic retry logic with Sentry integration for all failures

### 🔍 Search & Discovery
- **Multi-Vector Search**: 6 specialized embeddings (text, visual, color, texture, application, multimodal)
- **Duplicate Detection**: Smart material deduplication with factory/manufacturer matching
- **Search Suggestions**: AI-powered auto-complete, trending searches, and typo correction
- **Material Recognition**: Llama 4 Scout 17B Vision (69.4% MMMU, #1 OCR performance)
- **Relevancy System**: Multi-source linking between chunks, images, and products

### 💼 Quote & CRM System
- **Quote Management**: Complete quote system with status tags, upsells/extras, and project timeline tracking
- **Project Timeline**: 9-step visual timeline with admin updates and customer progress tracking
- **Custom Requests**: Support for text-based quote requests without products
- **CRM Integration**: User management with role-based access and subscription tracking
- **Status Tags**: Customizable quote status workflow with filtering and sorting

### 📊 Monitoring & Analytics
- **Analytics Dashboard**: Comprehensive metrics for search, API usage, PDF processing, and quality
- **Async Job Queue Monitor**: Real-time job tracking with 7 compact metrics and live updates
- **AI Model Tracking**: Monitor which models are used at each pipeline stage
- **Cost Tracking**: Track API costs across all AI providers (Anthropic, OpenAI, Together AI)
- **Performance Metrics**: Processing time, success rates, and resource utilization

### ⚙️ Admin & Configuration
- **Prompt Enhancement**: Admin-configurable extraction prompts with version control
- **AI Model Selection**: API-configurable model selection for each processing stage
- **Knowledge Base**: User-created documentation with PDF upload and markdown editor
- **Metadata Management**: Configure extraction categories and discovery prompts
- **System Settings**: Centralized configuration for all platform features

---

**Material Kai Vision Platform v2.3.0** - AI-powered material intelligence system with real-time monitoring & analytics

*This documentation is automatically generated and deployed from the main repository.*
*Last updated: $(date +"%Y-%m-%d %H:%M:%S UTC")*
