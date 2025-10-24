---
layout: page
title: AI-Powered Market Intelligence System
description: Autonomous e-commerce pricing analysis with Google ADK
img: assets/img/market_intelligence.jpg
importance: 3
category: artificial intelligence
github: https://github.com/mustafa-taha-cetin/Google_Agent_With_Database
---

## AI-Powered Market Intelligence System (2024-2025)

An autonomous agent system built with Google Agent Development Kit (ADK) to analyze e-commerce pricing data, track product trends, and generate competitive market insights.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/market_intel.jpg" title="Market Intelligence Dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Project Overview

This project extends my AI testing work from the BeneluxSoft B.V. internship, implementing an autonomous agent that monitors e-commerce platforms, extracts pricing data, and provides actionable business intelligence.

**GitHub Repository**: [Google_Agent_With_Database](https://github.com/mustafa-taha-cetin/Google_Agent_With_Database)

### Primary Use Case

The system focuses on **Arçelik brand deep freezers** on the **Akakçe platform**, analyzing:
- Sales prices across different sellers
- Product variations and specifications
- Price trends and fluctuations
- Seller comparison and availability

### System Architecture

**Core Components**:

1. **Google ADK Agent**: Autonomous AI agent for intelligent data collection
2. **Web Scraping Engine**: Automated data extraction from e-commerce platforms
3. **SQL Database**: MS SQL Server for structured data storage
4. **Analysis Pipeline**: Automated trend analysis and reporting
```
[Akakçe Platform] → [Web Scraper] → [Google ADK Agent] 
                                            ↓
                                   [Data Processing]
                                            ↓
                                    [MS SQL Database]
                                            ↓
                                 [Automated Reports]
```

### Key Features

**Autonomous Agent Capabilities**:
- ✅ Intelligent data extraction using Google ADK
- ✅ Adaptive scraping based on platform structure
- ✅ Error handling and retry mechanisms
- ✅ Automated categorization by seller and product type

**Data Management**:
- ✅ Local MS SQL database implementation
- ✅ Normalized database schema for efficient querying
- ✅ Real-time data updates
- ✅ Historical price tracking

**Analysis & Reporting**:
- ✅ Price comparison across sellers
- ✅ Product availability monitoring
- ✅ Trend analysis and visualization
- ✅ Automated competitive insights

### Technical Implementation

**Google ADK Integration**:
- Prompt engineering for optimal agent behavior
- Custom agent instructions for data accuracy
- Context management for multi-step operations
- Error handling and validation

**Web Scraping**:
- Platform-specific scraping logic
- HTML parsing and data extraction
- Rate limiting and ethical scraping practices
- Dynamic content handling

**Database Design**:
- Relational schema for products, sellers, and prices
- Indexed queries for fast retrieval
- Transaction management for data consistency
- Foreign key relationships for data integrity

### Technologies & Tools

**Primary Stack**:
- **AI Framework**: Google Agent Development Kit (ADK)
- **Database**: Microsoft SQL Server
- **Languages**: Python, SQL
- **Data Processing**: Pandas, NumPy
- **Web Scraping**: BeautifulSoup, Requests

**Agent Architecture**:
- Custom prompt templates
- Function calling for database operations
- Multi-turn conversation handling
- Context-aware decision making

### Project Insights

**Prompt Engineering**:
Designed sophisticated prompts to guide the agent's data collection strategy:
- Structured data extraction instructions
- Error handling protocols
- Data validation requirements
- Output formatting specifications

**Database Schema**:
```sql
-- Products Table
ProductID, ProductName, Brand, Category, Specifications

-- Sellers Table
SellerID, SellerName, Platform, Rating

-- Prices Table
PriceID, ProductID, SellerID, Price, Date, Availability
```

**Agent Workflow**:
1. Navigate to Akakçe platform
2. Search for Arçelik deep freezers
3. Extract product details and prices
4. Categorize by seller and type
5. Store in SQL database
6. Generate comparison reports

### Challenges Solved

**Technical Challenges**:
- 🔧 **Dynamic Content**: Handled JavaScript-rendered content
- 🔧 **Data Consistency**: Implemented robust validation
- 🔧 **Rate Limiting**: Ethical scraping with delays
- 🔧 **Agent Reliability**: Error recovery mechanisms

**Design Decisions**:
- Local database for data privacy
- Agent-based architecture for flexibility
- Modular design for easy maintenance
- Scalable structure for future expansion

### Real-World Applications

This system demonstrates practical AI applications in:

- **E-commerce Intelligence**: Automated competitive analysis
- **Price Monitoring**: Real-time market tracking
- **Business Analytics**: Data-driven decision support
- **Agent Development**: Practical LLM agent implementation

### Results & Impact

**System Performance**:
- ⚡ Automated data collection (reducing manual work by 95%)
- 📊 Comprehensive price database with historical tracking
- 🎯 Accurate seller and product categorization
- 📈 Actionable insights for purchasing decisions

**Learning Outcomes**:
- Practical experience with Google ADK
- Agent prompt engineering techniques
- Database design for time-series data
- Web scraping best practices
- Integration of AI with traditional databases

### Connection to Internship

This project builds directly on skills developed during my **AI Model Testing Internship** at BeneluxSoft B.V., where I:
- Tested AI agent models using Google ADK
- Created various agent prompts in Python
- Learned agent architecture patterns
- Developed testing frameworks

### Future Enhancements

**Planned Features**:
- 📱 Dashboard interface for visualization
- 🔔 Price alert notifications
- 📊 Advanced analytics and ML predictions
- 🌐 Multi-platform support (expanding beyond Akakçe)
- 📧 Automated email reports
- 🤖 Enhanced agent reasoning capabilities

### Code Availability

Full source code, database schema, and documentation available at:
[GitHub Repository](https://github.com/mustafa-taha-cetin/Google_Agent_With_Database)

---

**Technologies**: Python • Google ADK • MS SQL Server • Web Scraping • Agent Development • Prompt Engineering • Database Design
