# SuperClaude Usage Guide

A comprehensive guide to using SuperClaude's 19 commands, 9 personas, and extensive flag system across real-world development scenarios.

## 📋 Quick Reference

### Core Commands
- **Development**: `build`, `dev-setup`, `test`
- **Analysis**: `analyze`, `scan`, `review`, `troubleshoot`, `improve`, `explain`
- **Operations**: `deploy`, `migrate`, `cleanup`, `git`
- **Design**: `design`, `document`, `estimate`
- **Management**: `task`, `load`, `spawn`

### Universal Flags
- **Planning**: `--plan` (show execution plan)
- **Thinking**: `--think`, `--think-hard`, `--ultrathink`
- **Compression**: `--uc`, `--ultracompressed`
- **MCP**: `--c7`, `--seq`, `--magic`, `--pup`, `--pup-headless`, `--playwright`, `--mongodb-localhost`, `--memory`, `--fetch`, `--time`, `--mermaid`, `--helm`, `--argocd`, `--jira`, `--confluence`, `--excel`, `--openapi`, `--nixos`, `--pandoc`, `--elasticsearch`, `--all-mcp`, `--no-mcp`
- **Personas**: `--persona-architect`, `--persona-frontend`, `--persona-backend`, `--persona-analyzer`, `--persona-security`, `--persona-mentor`, `--persona-refactorer`, `--persona-performance`, `--persona-qa`
- **Introspection**: `--introspect`
- **Development**: `--ddd`, `--tdd`, `--human-review` (enabled by default, use `--no-ddd`, `--no-tdd`, `--no-human-review` to disable)

## 🎭 Persona-Driven Workflows

### 🏗️ Systems Architect Workflows

**Architecture Review & Planning**
```bash
# Enterprise system design
/design --api --ddd --bounded-context --persona-architect --think-hard

# Estimate complex system
/estimate --detailed --worst-case --complexity --persona-architect --seq

# Validate architecture
/analyze --architecture --scalability --persona-architect --seq --c7
```

**Migration Planning**
```bash
# Plan database migration
/migrate --dry-run --rollback --persona-architect --plan --seq

# Analyze migration impact
/analyze --architecture --dependencies --persona-architect --think-hard

# Document migration strategy
/document --api --technical --persona-architect --c7
```

### 🎨 Frontend Developer Workflows

**Component Development**
```bash
# Create React component with design system
/build --react --magic --accessibility --persona-frontend --watch

# Test component interactively
/test --e2e --visual --interaction --persona-frontend --pup

# Optimize for performance
/improve --performance --accessibility --persona-frontend --magic --pup
```

**UI/UX Focus**
```bash
# Design responsive interface
/design --responsive --accessibility --persona-frontend --magic --visual

# Build with real-time feedback
/build --react --magic --watch --persona-frontend --interactive

# Performance validation
/analyze --profile --performance --persona-frontend --pup --iterate
```

### ⚙️ Backend Developer Workflows

**API Development**
```bash
# Design scalable API
/design --api --rest --scalability --persona-backend --think-hard --c7

# Build with monitoring
/build --api --monitoring --performance --persona-backend --tdd

# Load testing
/test --integration --load --reliability --persona-backend --coverage
```

**Database Operations**
```bash
# Analyze database performance
/analyze --database --performance --persona-backend --profile --seq

# Optimize queries
/improve --database --query-optimization --persona-backend --iterate

# Migration with safety
/migrate --rollback --checkpoint --persona-backend --validate --plan
```

### 🔍 Security Specialist Workflows

**Security Audit**
```bash
# Comprehensive security scan
/scan --security --owasp --deps --secrets --persona-security --strict

# Threat modeling
/analyze --security --threats --compliance --persona-security --seq

# Security improvements
/improve --security --harden --validate --persona-security --coverage
```

**Compliance & Vulnerability Management**
```bash
# Security review
/review --security --compliance --persona-security --evidence --strict

# Vulnerability assessment
/troubleshoot --security --vulnerabilities --persona-security --seq

# Security documentation
/document --security --compliance --persona-security --c7 --visual
```

### 🔬 Analyzer Workflows

**Root Cause Investigation**
```bash
# Deep problem analysis
/troubleshoot --investigate --root-cause --persona-analyzer --ultrathink --seq

# Evidence-based debugging
/analyze --debug --evidence --persona-analyzer --seq --c7

# Performance bottleneck analysis
/analyze --profile --bottlenecks --persona-analyzer --pup --seq
```

**Quality Forensics**
```bash
# Code quality investigation
/analyze --code --quality --persona-analyzer --seq --evidence

# System behavior analysis
/troubleshoot --system --behavior --persona-analyzer --think-hard --seq

# Performance regression analysis
/analyze --performance --regression --persona-analyzer --profile --iterate
```

### 🧪 QA Specialist Workflows

**Comprehensive Testing**
```bash
# Full test suite
/test --coverage --e2e --integration --mutation --persona-qa --strict

# Quality validation
/scan --validate --quality --compliance --persona-qa --comprehensive

# Test automation
/test --automation --regression --persona-qa --pup --watch
```

**Quality Assurance**
```bash
# Quality gate validation
/review --quality --standards --persona-qa --evidence --strict

# Edge case testing
/test --edge-cases --boundary --persona-qa --pup --coverage

# Quality metrics
/analyze --quality --metrics --persona-qa --iterate --threshold 95%
```

### ⚡ Performance Engineer Workflows

**Performance Optimization**
```bash
# Performance profiling
/analyze --profile --bottlenecks --resource-usage --persona-performance --pup

# Optimization implementation
/improve --performance --cache --optimize --persona-performance --iterate

# Performance testing
/test --performance --load --stress --persona-performance --pup --monitoring
```

**Monitoring & Metrics**
```bash
# Performance monitoring setup
/deploy --monitoring --performance --persona-performance --watch

# Benchmark analysis
/analyze --benchmark --performance --persona-performance --profile --seq

# Performance documentation
/document --performance --optimization --persona-performance --c7 --visual
```

### 🔧 Refactoring Specialist Workflows

**Code Quality Improvement**
```bash
# Code quality analysis
/analyze --code --quality --complexity --persona-refactorer --seq

# Refactoring implementation
/improve --quality --refactor --maintainability --persona-refactorer --iterate

# Quality validation
/test --quality --regression --persona-refactorer --coverage --strict
```

**Technical Debt Management**
```bash
# Technical debt assessment
/analyze --technical-debt --maintainability --persona-refactorer --seq

# Cleanup operations
/cleanup --code --duplicates --persona-refactorer --validate --all

# Quality metrics tracking
/analyze --quality --metrics --persona-refactorer --iterate --evidence
```

### 👨‍🏫 Mentor Workflows

**Knowledge Transfer**
```bash
# Create learning materials
/document --tutorial --beginner --persona-mentor --c7 --examples

# Explain complex concepts
/explain --depth beginner --visual --persona-mentor --c7 --examples

# Team mentoring
/analyze --learning --knowledge-transfer --persona-mentor --seq --c7
```

**Documentation & Training**
```bash
# API documentation
/document --api --user-friendly --persona-mentor --c7 --visual

# Best practices guide
/document --best-practices --standards --persona-mentor --evidence --c7

# Interactive tutorials
/explain --interactive --step-by-step --persona-mentor --examples --visual
```

## 🔄 Multi-Persona Workflows

### Enterprise Architecture Review
```bash
# 1. Architecture Analysis (Architect)
/analyze --architecture --system --persona-architect --seq --think-hard

# 2. Security Review (Security)
/scan --security --architecture --persona-security --seq --strict

# 3. Performance Assessment (Performance)
/analyze --performance --scalability --persona-performance --profile --seq

# 4. Quality Validation (QA)
/scan --quality --validate --persona-qa --comprehensive --strict
```

### Full-Stack Feature Development
```bash
# 1. Design Phase (Architect)
/design --api --ddd --persona-architect --think-hard --c7

# 2. Backend Implementation (Backend)
/build --api --tdd --persona-backend --coverage --monitor

# 3. Frontend Implementation (Frontend)
/build --react --magic --persona-frontend --accessibility --watch

# 4. Quality Assurance (QA)
/test --e2e --integration --persona-qa --pup --coverage --strict

# 5. Security Review (Security)
/scan --security --validate --persona-security --comprehensive

# 6. Performance Testing (Performance)
/test --performance --load --persona-performance --pup --threshold 95%
```

### Production Issue Resolution
```bash
# 1. Initial Analysis (Analyzer)
/troubleshoot --investigate --prod --persona-analyzer --ultrathink --seq

# 2. Root Cause Investigation (Analyzer)
/analyze --debug --evidence --persona-analyzer --seq --c7

# 3. Performance Impact (Performance)
/analyze --profile --impact --persona-performance --pup --monitor

# 4. Security Assessment (Security)
/scan --security --incident --persona-security --seq --validate

# 5. Quality Validation (QA)
/test --regression --validation --persona-qa --coverage --strict

# 6. Documentation (Mentor)
/document --incident --post-mortem --persona-mentor --c7 --visual
```

## 🎯 Task-Specific Scenarios

### New Project Setup
```bash
# 1. Load project context
/load --context --environment

# 2. Development environment setup
/dev-setup --install --ci --docker --persona-architect

# 3. Initial project structure
/build --init --stack react-node --persona-architect --plan

# 4. Testing framework setup
/test --init --framework jest --persona-qa --coverage

# 5. Security baseline
/scan --security --baseline --persona-security --validate

# 6. Documentation setup
/document --init --structure --persona-mentor --c7
```

### Code Review Process
```bash
# 1. Automated review
/review --files --quality --persona-qa --evidence --strict

# 2. Security review
/review --security --vulnerabilities --persona-security --comprehensive

# 3. Performance review
/review --performance --bottlenecks --persona-performance --profile

# 4. Architecture review
/review --architecture --patterns --persona-architect --seq --c7

# 5. Quality metrics
/analyze --quality --metrics --persona-refactorer --evidence
```

### Deployment Pipeline
```bash
# 1. Pre-deployment validation
/scan --validate --comprehensive --persona-qa --strict

# 2. Security scan
/scan --security --owasp --deps --persona-security --strict

# 3. Performance baseline
/test --performance --baseline --persona-performance --pup

# 4. Staging deployment
/deploy --env staging --monitor --persona-backend --validate

# 5. E2E testing
/test --e2e --staging --persona-qa --pup --coverage

# 6. Production deployment
/deploy --env prod --rollback --persona-backend --checkpoint --plan
```

### Performance Optimization
```bash
# 1. Performance profiling
/analyze --profile --comprehensive --persona-performance --pup --seq

# 2. Bottleneck identification
/analyze --bottlenecks --resources --persona-performance --profile

# 3. Optimization implementation
/improve --performance --cache --optimize --persona-performance --iterate

# 4. Performance testing
/test --performance --load --stress --persona-performance --pup

# 5. Monitoring setup
/deploy --monitoring --performance --persona-performance --watch

# 6. Documentation
/document --performance --optimization --persona-mentor --c7 --visual
```

### Security Hardening
```bash
# 1. Security baseline assessment
/scan --security --baseline --persona-security --comprehensive

# 2. Threat modeling
/analyze --security --threats --persona-security --seq --think-hard

# 3. Vulnerability scanning
/scan --security --owasp --deps --secrets --persona-security --strict

# 4. Security improvements
/improve --security --harden --validate --persona-security --coverage

# 5. Penetration testing
/test --security --penetration --persona-security --pup --comprehensive

# 6. Security documentation
/document --security --compliance --persona-security --c7 --visual
```

## 🚀 Advanced Flag Combinations

### Deep Analysis Workflows
```bash
# Maximum analysis depth
/analyze --architecture --seq --think-hard --ultrathink --c7

# Comprehensive system analysis
/analyze --system --dependencies --persona-architect --seq --all-mcp

# Performance deep dive
/analyze --profile --bottlenecks --persona-performance --pup --seq --iterate
```

### High-Performance Development
```bash
# Rapid UI development
/build --react --magic --watch --persona-frontend --interactive

# Efficient backend development
/build --api --tdd --watch --persona-backend --coverage --monitor

# Performance-focused testing
/test --performance --load --pup --persona-performance --iterate --threshold 95%
```

### Token-Optimized Workflows
```bash
# Compressed documentation
/document --api --uc --persona-mentor --c7

# Efficient analysis
/analyze --code --uc --no-mcp --persona-refactorer

# Rapid deployment
/deploy --env prod --uc --persona-backend --validate
```

### Collaborative Debugging
```bash
# Transparent investigation
/troubleshoot --investigate --introspect --persona-analyzer --seq

# Learning-focused debugging
/troubleshoot --debug --introspect --persona-mentor --c7 --visual

# Team debugging session
/troubleshoot --collaborative --introspect --persona-analyzer --think-hard
```

## 🛠️ MCP Server Optimization

### Context7 (AI-Powered Documentation Research)

**Overview**
Context7 is an intelligent documentation retrieval system that provides instant access to library and framework documentation. It can resolve library names and fetch targeted documentation based on your queries.

**Installation**
```bash
# Install Context7 MCP server
claude mcp add context7 -- npx -y @upstash/context7-mcp
```

**Basic Documentation Lookup**
```bash
# Simple library documentation
/explain --c7 "How to use React hooks"

# Specific library with known ID
/build --c7 "Implement authentication with /supabase/supabase"

# Framework patterns
/analyze --c7 --patterns "Next.js routing best practices"

# API documentation
/design --c7 --api "GraphQL schema design with /apollographql/apollo-server"
```

**Library Resolution Examples**
```bash
# Automatic library detection
/explain --c7 "How to create a REST API with Express"
# Context7 resolves: express → /expressjs/express

# Multiple library context
/build --c7 "Build a full-stack app with React and MongoDB"
# Context7 resolves both: react → /facebook/react, mongodb → /mongodb/node-mongodb-native

# Framework-specific queries
/analyze --c7 "Vue 3 composition API patterns"
# Context7 resolves: vue → /vuejs/core

# Testing libraries
/test --c7 "Write unit tests with Jest and React Testing Library"
# Context7 resolves: jest → /facebook/jest, testing-library → /testing-library/react-testing-library
```

**Targeted Topic Research**
```bash
# Focus on specific topics
/explain --c7 "React hooks" --topic "useEffect cleanup"

# Authentication patterns
/build --c7 "/auth0/node-auth0" --topic "JWT validation"

# Database operations
/design --c7 "/prisma/prisma" --topic "migrations"

# State management
/analyze --c7 "Redux Toolkit" --topic "async thunks"
```

**Integration Workflows**
```bash
# Full-stack development
/build --c7 --react "Create user dashboard with /tanstack/react-query for data fetching"

# API development
/design --c7 --api "Build GraphQL API with /graphql/graphql-js and /prisma/prisma"

# Authentication setup
/build --c7 --secure "Implement OAuth with /nextauthjs/next-auth"

# Database integration
/migrate --c7 --mongodb-localhost "Set up MongoDB with /mongoose/mongoose"
```

**Advanced Usage Patterns**
```bash
# Multi-library documentation
/build --c7 --comprehensive "Create app with /vercel/next.js, /tailwindlabs/tailwindcss, and /vercel/swr"

# Migration guides
/migrate --c7 "Migrate from Express to /fastify/fastify"

# Performance optimization
/improve --c7 --performance "Optimize React with /facebook/react profiler and /tanstack/react-virtual"

# Testing strategies
/test --c7 --comprehensive "Test with /cypress-io/cypress and /facebook/jest"
```

**Token Management**
```bash
# Default token limit (10000)
/explain --c7 "Comprehensive Next.js guide"

# Extended documentation
/analyze --c7 --tokens 20000 "Complete AWS SDK documentation"

# Concise summaries (minimum 10000)
/explain --c7 --tokens 5000 "Quick Redis overview"
# Note: Automatically increased to 10000
```

**Common Library IDs**
```bash
# Frontend frameworks
/facebook/react - React documentation
/vuejs/core - Vue.js documentation
/angular/angular - Angular documentation
/sveltejs/svelte - Svelte documentation

# Backend frameworks
/expressjs/express - Express.js
/fastify/fastify - Fastify
/nestjs/nest - NestJS
/koajs/koa - Koa

# Databases
/mongodb/node-mongodb-native - MongoDB Node driver
/prisma/prisma - Prisma ORM
/mongoose/mongoose - Mongoose ODM
/redis/node-redis - Redis client

# Testing
/facebook/jest - Jest testing
/cypress-io/cypress - Cypress E2E
/testing-library/react-testing-library - React Testing Library
/mochajs/mocha - Mocha

# Build tools
/vitejs/vite - Vite
/webpack/webpack - Webpack
/vercel/turbo - Turborepo
```

**Workflow Examples**
```bash
# New project setup
/build --c7 --init "Set up Next.js project with TypeScript"
/design --c7 "Configure /vercel/next.js with /tailwindlabs/tailwindcss"
/test --c7 "Add testing with /facebook/jest and /testing-library/react-testing-library"

# API development
/design --c7 --api "Design REST API with /expressjs/express"
/build --c7 "Add authentication with /auth0/node-auth0"
/document --c7 "Generate API docs with /swagger-api/swagger-ui"

# Database setup
/analyze --c7 "Compare /prisma/prisma vs /typeorm/typeorm"
/migrate --c7 "Set up PostgreSQL with /prisma/prisma"
/build --c7 "Create models and migrations"
```

**Best Practices**

1. **Use Specific Library IDs When Known**
   ```bash
   # Good: Direct library reference
   /build --c7 "Implement auth with /clerk/clerk-sdk-node"
   
   # Also works: Let Context7 resolve
   /build --c7 "Implement auth with Clerk"
   ```

2. **Combine with Personas**
   ```bash
   # Backend focus
   /design --c7 --persona-backend "API patterns with /nestjs/nest"
   
   # Frontend optimization
   /improve --c7 --persona-frontend "React performance with /facebook/react"
   ```

3. **Focus Topics for Efficiency**
   ```bash
   # Targeted documentation
   /explain --c7 "/mongodb/node-mongodb-native" --topic "aggregation pipelines"
   ```

4. **Chain Documentation Lookups**
   ```bash
   # Progressive learning
   /explain --c7 "React basics"
   /explain --c7 "React hooks" --topic "custom hooks"
   /build --c7 "Advanced patterns with /facebook/react"
   ```

**Integration with Other MCP Servers**
```bash
# Context7 + Magic for UI
/design --c7 --magic "Create components with /facebook/react and /emotion-js/emotion"

# Context7 + MongoDB for data layer
/build --c7 --mongodb-localhost "Set up /mongoose/mongoose with local MongoDB"

# Context7 + Playwright for testing
/test --c7 --playwright "E2E tests with /playwright/playwright"
```

**Tips for Success**
- Use library IDs for faster, more accurate results
- Specify topics to get focused documentation
- Combine with `--seq` for complex analysis
- Use `--think-hard` when comparing multiple libraries
- Include version numbers when needed (e.g., "React 18")

### Sequential Thinking (Structured Problem-Solving)

**Overview**
Sequential Thinking is a powerful MCP server that enables structured, step-by-step problem-solving with dynamic revision capabilities. It excels at breaking down complex problems, maintaining context across multiple steps, and adapting the solution path as understanding deepens.

**Installation**
```bash
# Install Sequential Thinking MCP server
claude mcp add sequential -- npx -y @modelcontextprotocol/server-sequential-thinking
```

**Basic Problem Decomposition**
```bash
# Simple step-by-step analysis
/analyze --seq "Break down the authentication flow"

# Complex system design
/design --seq --think-hard "Design a microservices architecture"

# Debugging with sequential steps
/troubleshoot --seq "Find the memory leak in our application"

# Algorithm development
/build --seq "Implement a distributed caching system"
```

**Architecture & System Design**
```bash
# Multi-step architecture planning
/design --seq --persona-architect --think-hard "Design scalable e-commerce platform"
# Thought 1: Identify core components (users, products, orders)
# Thought 2: Design service boundaries
# Thought 3: Plan data flow between services
# Thought 4: Consider scaling strategies
# Revision: Adjust service boundaries based on data flow

# Database schema evolution
/design --seq --mongodb-localhost "Design schema for social media app"
# Progressive refinement through multiple thoughts
# Branches for different normalization strategies

# API design with iterations
/design --seq --api "Create REST API for payment processing"
# Sequential thoughts building on each other
# Revisions as requirements become clearer
```

**Root Cause Analysis**
```bash
# Performance investigation
/troubleshoot --seq --persona-analyzer "Application responds slowly under load"
# Thought 1: Identify bottleneck symptoms
# Thought 2: Analyze database queries
# Thought 3: Check memory usage patterns
# Branch A: Investigate caching strategies
# Branch B: Explore query optimization

# Bug investigation with branching
/troubleshoot --seq --ultrathink "Users report intermittent login failures"
# Multiple investigation paths
# Revisions as new evidence emerges
# Dynamic thought count adjustment

# System failure analysis
/analyze --seq --evidence "Production outage root cause"
# Step-by-step forensic analysis
# Branching for different failure scenarios
```

**Complex Refactoring**
```bash
# Legacy code modernization
/improve --seq --refactor "Modernize monolithic application"
# Thought 1: Analyze current architecture
# Thought 2: Identify bounded contexts
# Thought 3: Plan extraction strategy
# Thought 4: Design transition approach
# Revisions based on discovered dependencies

# Performance optimization journey
/improve --seq --performance --iterate "Optimize data processing pipeline"
# Sequential optimization strategies
# Measure and revise approach
# Branch for alternative solutions

# Code quality improvement
/improve --seq --quality "Refactor complex business logic"
# Break down into manageable steps
# Revise as patterns emerge
```

**Algorithm Development**
```bash
# Complex algorithm design
/build --seq --algorithm "Implement recommendation engine"
# Thought 1: Define requirements and constraints
# Thought 2: Research collaborative filtering
# Thought 3: Design data structures
# Thought 4: Plan implementation phases
# Branch: Explore content-based filtering

# Distributed system algorithms
/design --seq --distributed "Design consensus algorithm"
# Progressive refinement
# Multiple solution branches
# Revisions for edge cases

# Machine learning pipeline
/build --seq --ml "Create fraud detection system"
# Sequential feature engineering
# Model selection thoughts
# Revision based on validation results
```

**Migration Planning**
```bash
# Database migration strategy
/migrate --seq --plan "Migrate from PostgreSQL to MongoDB"
# Thought 1: Analyze data models
# Thought 2: Map relational to document structure
# Thought 3: Plan migration phases
# Thought 4: Design rollback strategy
# Revisions as complexities discovered

# Cloud migration planning
/migrate --seq --cloud "Move on-premise to AWS"
# Sequential dependency mapping
# Branch for different service migrations
# Dynamic thought expansion

# Technology stack migration
/migrate --seq "Migrate from Angular to React"
# Component-by-component planning
# Revision points for shared state
# Branching for different approaches
```

**Feature Development Workflow**
```bash
# Complex feature planning
/build --seq --feature --plan "Implement real-time collaboration"
# Thought 1: Define collaboration requirements
# Thought 2: Research WebSocket vs SSE
# Thought 3: Design state synchronization
# Thought 4: Plan conflict resolution
# Branch: Alternative architectures

# Multi-phase implementation
/build --seq --tdd "Add shopping cart functionality"
# Sequential test-driven thoughts
# Revisions after each test phase
# Branches for edge cases

# Integration planning
/build --seq --integrate "Add payment gateway"
# Step-by-step integration thoughts
# Revisions for API discoveries
# Branches for different providers
```

**Problem-Solving Patterns**
```bash
# Research and exploration
/analyze --seq --research "Evaluate authentication strategies"
# Thought 1: JWT vs Session comparison
# Thought 2: Security implications
# Thought 3: Scalability considerations
# Branch A: OAuth integration
# Branch B: Custom implementation

# Decision making process
/analyze --seq --decision "Choose frontend framework"
# Progressive evaluation criteria
# Revisions as priorities clarify
# Branches for different use cases

# Capacity planning
/analyze --seq --capacity "Plan for 10x growth"
# Sequential scaling thoughts
# Revisions based on bottlenecks
# Branches for different scenarios
```

**Advanced Sequential Patterns**
```bash
# Multi-branch exploration
/design --seq --explore "Design notification system"
# Branch 1: Push notifications
# Branch 2: Email notifications
# Branch 3: In-app notifications
# Merge: Unified notification service

# Iterative refinement
/improve --seq --iterate --threshold 95 "Optimize search algorithm"
# Thought → Measure → Revise cycle
# Dynamic thought count based on progress
# Multiple optimization branches

# Hypothesis-driven development
/build --seq --hypothesis "Improve user engagement"
# Thought 1: Form hypothesis
# Thought 2: Design experiment
# Thought 3: Implement changes
# Thought 4: Analyze results
# Revision: Adjust based on data
```

**Integration with Other Tools**
```bash
# Sequential + Context7 for research
/analyze --seq --c7 "Learn and implement GraphQL"
# Sequential learning path
# Documentation lookups at each step

# Sequential + Magic for UI design
/design --seq --magic "Create admin dashboard"
# Progressive UI component thoughts
# Revisions based on generated components

# Sequential + MongoDB for data modeling
/design --seq --mongodb-localhost "Design analytics schema"
# Step-by-step schema evolution
# Revisions after test queries
```

**Best Practices**

1. **Start Broad, Then Focus**
   ```bash
   # Initial thought: Overview
   # Subsequent thoughts: Detailed exploration
   # Revisions: Refined understanding
   ```

2. **Use Branches for Alternatives**
   ```bash
   # Main path: Primary solution
   # Branch A: Alternative approach
   # Branch B: Fallback strategy
   ```

3. **Leverage Revisions**
   ```bash
   # Don't hesitate to revise earlier thoughts
   # New information changes understanding
   # Revisions show learning process
   ```

4. **Dynamic Thought Management**
   ```bash
   # Start with estimated thought count
   # Adjust as complexity emerges
   # Use needsMoreThoughts when necessary
   ```

**Common Patterns**
```bash
# Investigation Pattern
/troubleshoot --seq "Debug issue"
# 1. Symptoms → 2. Hypotheses → 3. Tests → 4. Solution

# Design Pattern
/design --seq "Create system"
# 1. Requirements → 2. Architecture → 3. Components → 4. Integration

# Optimization Pattern
/improve --seq "Enhance performance"
# 1. Baseline → 2. Bottlenecks → 3. Solutions → 4. Validation

# Learning Pattern
/analyze --seq "Understand technology"
# 1. Overview → 2. Deep dive → 3. Practice → 4. Mastery
```

**Tips for Success**
- Use Sequential for problems with unknown scope
- Branch when multiple valid approaches exist
- Revise thoughts as understanding improves
- Combine with --think-hard for complex problems
- Track thought numbers for complex branches
- Use descriptive branch IDs for clarity

### Memory (Persistent Knowledge Graph)

**Overview**
Memory is a knowledge graph server that provides persistent memory across sessions. It enables Claude to remember information about users, projects, preferences, and relationships through a structured graph of entities and their connections.

**Installation**
```bash
# Install Memory MCP server
claude mcp add memory -- npx -y @modelcontextprotocol/server-memory
```

**Core Concepts**

1. **Entities**: Primary nodes with unique names, types, and observations
2. **Relations**: Directed connections between entities (always in active voice)
3. **Observations**: Atomic facts attached to entities

**Basic Memory Operations**
```bash
# Remember user information
/task --memory "Remember that John Smith prefers TypeScript and works at Anthropic"

# Recall stored information
/analyze --memory "What do we know about John Smith?"

# Update project context
/build --memory "Store that Project Alpha uses React 18 and Node.js 20"

# Query relationships
/analyze --memory "Show all team members and their roles"
```

**Entity Management**
```bash
# Create user entities
/task --memory create-entities '[
  {
    "name": "John_Smith",
    "entityType": "person",
    "observations": [
      "Prefers TypeScript over JavaScript",
      "Senior Full-Stack Developer",
      "Timezone: PST",
      "Prefers morning meetings"
    ]
  }
]'

# Create project entities
/task --memory create-entities '[
  {
    "name": "Project_Alpha",
    "entityType": "project",
    "observations": [
      "E-commerce platform",
      "Tech stack: React, Node.js, PostgreSQL",
      "Launch date: Q2 2025",
      "High priority"
    ]
  }
]'

# Create organization entities
/task --memory create-entities '[
  {
    "name": "Anthropic",
    "entityType": "organization",
    "observations": [
      "AI safety company",
      "Founded in 2021",
      "Headquarters: San Francisco"
    ]
  }
]'
```

**Relationship Building**
```bash
# Create work relationships
/task --memory create-relations '[
  {
    "from": "John_Smith",
    "to": "Anthropic",
    "relationType": "works_at"
  },
  {
    "from": "John_Smith",
    "to": "Project_Alpha",
    "relationType": "leads"
  }
]'

# Team relationships
/task --memory create-relations '[
  {
    "from": "Sarah_Chen",
    "to": "John_Smith",
    "relationType": "reports_to"
  },
  {
    "from": "Mike_Johnson",
    "to": "John_Smith",
    "relationType": "collaborates_with"
  }
]'

# Project dependencies
/task --memory create-relations '[
  {
    "from": "Project_Alpha",
    "to": "Auth_Service",
    "relationType": "depends_on"
  },
  {
    "from": "Project_Alpha",
    "to": "Payment_Gateway",
    "relationType": "integrates_with"
  }
]'
```

**Adding Observations**
```bash
# Add new facts to entities
/task --memory add-observations '[
  {
    "entityName": "John_Smith",
    "contents": [
      "Completed AWS certification",
      "Prefers VS Code",
      "Expert in microservices"
    ]
  }
]'

# Update project status
/task --memory add-observations '[
  {
    "entityName": "Project_Alpha",
    "contents": [
      "Completed authentication module",
      "Performance issues resolved",
      "Ready for beta testing"
    ]
  }
]'

# Track preferences
/task --memory add-observations '[
  {
    "entityName": "John_Smith",
    "contents": [
      "Prefers detailed code comments",
      "Uses conventional commits",
      "Likes TDD approach"
    ]
  }
]'
```

**Knowledge Retrieval**
```bash
# Read entire knowledge graph
/analyze --memory read-graph

# Search for specific information
/analyze --memory search "TypeScript"
/analyze --memory search "project status"
/analyze --memory search "team members"

# Open specific nodes
/analyze --memory open-nodes '["John_Smith", "Project_Alpha"]'

# Query relationships
/analyze --memory "Who works on Project Alpha?"
/analyze --memory "What technologies does John prefer?"
```

**Project Context Management**
```bash
# Store project architecture decisions
/design --memory --ddd "Store that we chose microservices for Project Alpha"

# Remember API design choices
/design --memory --api "Save that we use REST with JWT authentication"

# Track technical debt
/analyze --memory "Add observation: Project Alpha needs database optimization"

# Document dependencies
/build --memory "Remember Project Alpha depends on Redis for caching"
```

**Team Collaboration Memory**
```bash
# Team member preferences
/task --memory "Sarah prefers React hooks and functional components"

# Meeting decisions
/task --memory "Team decided to use GitHub Actions for CI/CD"

# Code review feedback
/review --memory "John suggested using dependency injection pattern"

# Sprint retrospectives
/task --memory "Team identified testing as improvement area for next sprint"
```

**Development Workflow Integration**
```bash
# Remember coding standards
/task --memory --tdd "Team follows red-green-refactor cycle"

# Track architecture decisions
/design --memory --seq "Decided on event-driven architecture for notifications"

# Store debugging insights
/troubleshoot --memory "Memory leak was caused by unclosed database connections"

# Document performance optimizations
/improve --memory --performance "Implemented caching reduced API response time by 60%"
```

**Advanced Patterns**
```bash
# Complex relationship mapping
/task --memory create-relations '[
  {"from": "Frontend_App", "to": "GraphQL_API", "relationType": "queries"},
  {"from": "GraphQL_API", "to": "User_Service", "relationType": "fetches_from"},
  {"from": "GraphQL_API", "to": "Product_Service", "relationType": "fetches_from"},
  {"from": "User_Service", "to": "PostgreSQL_DB", "relationType": "stores_in"}
]'

# Technology stack memory
/build --memory create-entities '[
  {
    "name": "Tech_Stack_2024",
    "entityType": "configuration",
    "observations": [
      "Frontend: React 18, TypeScript, Tailwind",
      "Backend: Node.js 20, Express, GraphQL",
      "Database: PostgreSQL 15, Redis",
      "Infrastructure: AWS, Docker, Kubernetes"
    ]
  }
]'

# Decision tracking
/task --memory create-entities '[
  {
    "name": "ADR_001_Authentication",
    "entityType": "decision",
    "observations": [
      "Date: 2024-01-15",
      "Decision: Use JWT with refresh tokens",
      "Rationale: Stateless, scalable, secure",
      "Alternatives considered: Sessions, OAuth only"
    ]
  }
]'
```

**Memory Maintenance**
```bash
# Remove outdated information
/cleanup --memory delete-observations '[
  {
    "entityName": "Project_Alpha",
    "observations": ["Uses React 16"]
  }
]'

# Delete obsolete entities
/cleanup --memory delete-entities '["Old_Project", "Former_Employee"]'

# Remove changed relationships
/cleanup --memory delete-relations '[
  {
    "from": "John_Smith",
    "to": "Old_Team",
    "relationType": "member_of"
  }
]'
```

**Integration with Other MCP Servers**
```bash
# Memory + Sequential for learning
/analyze --memory --seq "Learn about the project and create a development plan"

# Memory + Context7 for documentation
/document --memory --c7 "Create docs based on what we know about the API"

# Memory + Magic for UI consistency
/build --memory --magic "Create components matching our established design patterns"

# Memory + MongoDB for data modeling
/design --memory --mongodb-localhost "Design schema based on our entity relationships"
```

**Best Practices**

1. **Use Consistent Naming**
   ```bash
   # Good: Underscore for multi-word entities
   "John_Smith", "Project_Alpha", "Auth_Service"
   
   # Avoid: Inconsistent naming
   "john", "ProjectAlpha", "auth-service"
   ```

2. **Keep Observations Atomic**
   ```bash
   # Good: One fact per observation
   ["Prefers TypeScript", "Senior Developer", "PST timezone"]
   
   # Avoid: Multiple facts in one
   ["John is a senior dev who likes TypeScript and works in PST"]
   ```

3. **Use Active Voice for Relations**
   ```bash
   # Good: Active voice
   "John_Smith" → "works_at" → "Anthropic"
   
   # Avoid: Passive voice
   "Anthropic" → "employs" → "John_Smith"
   ```

4. **Regular Maintenance**
   ```bash
   # Periodically review and update
   /analyze --memory read-graph
   /cleanup --memory "Remove outdated observations"
   ```

**Common Use Cases**
```bash
# Onboarding new team member
/task --memory "Create entity for new developer Alice Wong with her preferences"

# Project handoff
/analyze --memory "Summarize everything about Project Alpha for handoff"

# Technical decision log
/task --memory "Record that we chose PostgreSQL over MongoDB for ACID compliance"

# Personal preferences
/task --memory "Remember that user prefers concise code comments"

# Bug tracking context
/troubleshoot --memory "Store that login bug occurs only with SSO users"
```

**Tips for Success**
- Build knowledge graph incrementally
- Use meaningful entity types (person, project, technology, decision)
- Create bidirectional relationships when appropriate
- Regularly query and verify stored information
- Combine with --human-review for important memory updates
- Use search to avoid duplicate entities

### Fetch (Web Content Retrieval)

**⚠️ Security Warning**
The Fetch server can access local/internal IP addresses and may represent a security risk. Exercise caution to ensure it doesn't expose sensitive data. Never use on untrusted URLs or internal resources without proper authorization.

**Overview**
Fetch is a web content retrieval server that fetches URLs and converts HTML to markdown for easier processing. It supports chunked reading for large pages and can retrieve raw content when needed.

**Installation**
```bash
# Install Fetch MCP server via Docker
claude mcp add fetch -- docker run -i --rm mcp/fetch
```

**Basic Web Content Retrieval**
```bash
# Fetch a webpage and convert to markdown
/analyze --fetch "https://example.com"

# Fetch with custom length limit
/analyze --fetch "https://docs.python.org/3/" --max-length 10000

# Get raw HTML content
/analyze --fetch "https://example.com" --raw true

# Read from specific position (for pagination)
/analyze --fetch "https://longpage.com" --start-index 5000
```

**Documentation Research**
```bash
# Fetch official documentation
/explain --fetch "https://react.dev/learn" --max-length 20000

# Research API documentation
/analyze --fetch "https://api.github.com/docs"

# Compare framework features
/analyze --fetch "https://vuejs.org/guide/" --seq
/analyze --fetch "https://react.dev/learn" --seq
```

**Content Analysis**
```bash
# Analyze website structure
/analyze --fetch "https://example.com/sitemap.xml" --raw

# Extract specific information
/troubleshoot --fetch "https://status.github.com" "Check service status"

# Security advisory research
/scan --fetch "https://nvd.nist.gov/vuln/detail/CVE-2024-1234" --security

# License verification
/analyze --fetch "https://opensource.org/licenses/MIT"
```

**Chunked Reading for Large Pages**
```bash
# Read documentation in chunks
/analyze --fetch "https://nodejs.org/docs/latest/api/" --max-length 5000 --start-index 0
/analyze --fetch "https://nodejs.org/docs/latest/api/" --max-length 5000 --start-index 5000
/analyze --fetch "https://nodejs.org/docs/latest/api/" --max-length 5000 --start-index 10000

# Progressive content extraction
/explain --fetch --seq "Read AWS documentation in chunks until finding S3 pricing"
# Automatically adjusts start_index to find relevant content
```

**Integration Workflows**
```bash
# Fetch + Context7 for comparison
/analyze --fetch "https://nextjs.org/docs" --c7 "/vercel/next.js"
# Compare official docs with Context7's indexed version

# Fetch + Sequential for research
/analyze --fetch --seq "Research React performance optimization techniques"
# Sequential thinking with web content

# Fetch + Memory for knowledge building
/task --fetch --memory "Fetch React best practices and store key insights"

# Fetch + Magic for inspiration
/build --fetch --magic "Analyze popular UI libraries for design patterns"
```

**API Documentation Fetching**
```bash
# REST API docs
/analyze --fetch "https://api.stripe.com/docs"

# GraphQL schemas
/analyze --fetch "https://api.github.com/graphql" --raw

# OpenAPI specifications
/analyze --fetch "https://petstore.swagger.io/v2/swagger.json" --raw

# SDK documentation
/explain --fetch "https://aws.amazon.com/sdk-for-javascript/"
```

**Research & Learning**
```bash
# Tutorial analysis
/explain --fetch "https://www.freecodecamp.org/news/react-tutorial/"

# Blog post extraction
/analyze --fetch "https://blog.example.com/microservices-best-practices"

# Stack Overflow answers
/troubleshoot --fetch "https://stackoverflow.com/questions/12345/react-hooks-error"

# GitHub README analysis
/analyze --fetch "https://raw.githubusercontent.com/facebook/react/main/README.md"
```

**Monitoring & Status Pages**
```bash
# Service status monitoring
/analyze --fetch "https://www.githubstatus.com/"
/analyze --fetch "https://status.aws.amazon.com/"

# Package registry info
/analyze --fetch "https://www.npmjs.com/package/react"

# Security bulletins
/scan --fetch "https://github.com/advisories" --security

# Release notes
/analyze --fetch "https://github.com/nodejs/node/releases/latest"
```

**Advanced Usage Patterns**
```bash
# Multi-page analysis
/analyze --fetch --seq "Compare pricing pages of major cloud providers"
# Fetches AWS, GCP, Azure pricing pages sequentially

# Content extraction with filtering
/analyze --fetch "https://news.ycombinator.com" "Extract top 5 tech stories"

# Changelog analysis
/analyze --fetch "https://github.com/facebook/react/blob/main/CHANGELOG.md" --max-length 20000

# Documentation migration
/migrate --fetch "https://v4.webpack.js.org/migrate/5/" --plan
```

**Security Best Practices**

1. **URL Validation**
   ```bash
   # Good: Public websites
   /analyze --fetch "https://public-docs.example.com"
   
   # Avoid: Internal resources
   # Never: /analyze --fetch "http://192.168.1.1/admin"
   # Never: /analyze --fetch "http://localhost:8080/private"
   ```

2. **Content Verification**
   ```bash
   # Verify SSL certificates
   /analyze --fetch "https://verified-site.com"
   
   # Check content type before processing
   /analyze --fetch "https://example.com/data.json" --raw
   ```

3. **Rate Limiting**
   ```bash
   # Respect rate limits
   /analyze --fetch "https://api.example.com" --plan
   # Add delays between requests when needed
   ```

4. **Data Handling**
   ```bash
   # Be cautious with sensitive data
   /analyze --fetch "https://public-api.com" --no-memory
   # Don't store sensitive fetched content
   ```

**Common Patterns**
```bash
# Documentation research pattern
/explain --fetch "https://docs.example.com" --max-length 10000
/analyze --fetch "https://docs.example.com/api" --start-index 10000

# Comparison pattern
/analyze --fetch "https://framework1.com/features" --memory
/analyze --fetch "https://framework2.com/features" --memory
/analyze --memory "Compare stored framework features"

# Progressive reading pattern
/analyze --fetch --seq "Read documentation until finding deployment section"
# Uses start_index dynamically to find specific content

# API exploration pattern
/analyze --fetch "https://api.example.com/v1/docs" 
/design --fetch "https://api.example.com/v1/openapi.json" --api
```

**Integration Examples**
```bash
# Research-driven development
/analyze --fetch "https://martinfowler.com/articles/microservices.html" --seq
/design --ddd --seq "Apply Martin Fowler's microservices patterns"

# Security audit workflow
/scan --fetch "https://owasp.org/www-project-top-ten/" --security
/analyze --security "Apply OWASP Top 10 to our application"

# Technology evaluation
/analyze --fetch "https://stateofjs.com/2024" --memory
/analyze --memory "Summarize JavaScript ecosystem trends"
```

**Error Handling**
```bash
# Handle timeouts
/analyze --fetch "https://slow-site.com" --timeout 30000

# Handle redirects
/analyze --fetch "https://bit.ly/shortened" 
# Automatically follows redirects

# Handle authentication
# Note: Fetch doesn't support auth headers
# Use for public content only
```

**Tips for Success**
- Always validate URLs before fetching
- Use max_length to control response size
- Leverage start_index for pagination
- Combine with --seq for multi-page analysis
- Use --raw for structured data (JSON, XML)
- Respect robots.txt and rate limits
- Never fetch internal/private resources
- Cache results with --memory when appropriate

### Time (Timezone & Time Utilities)

**Overview**
Time is a utility server that provides accurate time information and timezone conversion capabilities. It uses IANA timezone names and automatically detects system timezone for local time operations.

**Installation**
```bash
# Install Time MCP server via Docker
claude mcp add time -- docker run -i --rm mcp/time
```

**Basic Time Operations**
```bash
# Get current time in system timezone
/analyze --time "What time is it?"

# Get time in specific timezone
/analyze --time "Current time in America/New_York"
/analyze --time "What time is it in Europe/London?"
/analyze --time "Show time in Asia/Tokyo"
```

**Timezone Conversions**
```bash
# Convert time between timezones
/analyze --time "Convert 14:30 from America/New_York to Europe/London"

# Meeting scheduling across timezones
/analyze --time "Convert 10:00 AM PST to EST, CET, and JST"

# Complex conversions
/analyze --time "What time is 9:00 UTC in all US timezones?"
```

**Common IANA Timezones**
```bash
# Americas
America/New_York        # Eastern Time (US)
America/Chicago         # Central Time (US)
America/Denver          # Mountain Time (US)
America/Los_Angeles     # Pacific Time (US)
America/Toronto         # Eastern Time (Canada)
America/Vancouver       # Pacific Time (Canada)
America/Mexico_City     # Central Time (Mexico)
America/Sao_Paulo       # Brasília Time
America/Buenos_Aires    # Argentina Time

# Europe
Europe/London           # British Time
Europe/Paris            # Central European Time
Europe/Berlin           # Central European Time
Europe/Madrid           # Central European Time
Europe/Rome             # Central European Time
Europe/Moscow           # Moscow Time
Europe/Stockholm        # Central European Time
Europe/Amsterdam        # Central European Time

# Asia/Pacific
Asia/Tokyo              # Japan Standard Time
Asia/Shanghai           # China Standard Time
Asia/Hong_Kong          # Hong Kong Time
Asia/Singapore          # Singapore Time
Asia/Seoul              # Korea Standard Time
Asia/Kolkata            # India Standard Time
Asia/Dubai              # Gulf Standard Time
Australia/Sydney        # Australian Eastern Time
Australia/Melbourne     # Australian Eastern Time
Pacific/Auckland        # New Zealand Time
```

**Scheduling & Planning**
```bash
# Global meeting planning
/task --time "Find best meeting time for NYC, London, and Tokyo teams"

# Sprint planning across timezones
/task --time "Schedule daily standup for team in PST, EST, and IST"

# Release coordination
/deploy --time "Plan deployment window for minimal impact across regions"

# Follow-the-sun support
/analyze --time "Show support hours coverage: SF 9-5, London 9-5, Singapore 9-5"
```

**Development Workflows**
```bash
# CI/CD scheduling
/deploy --time "Schedule build at 2 AM EST"
/analyze --time "Convert cron schedule to different timezones"

# Log timestamp analysis
/troubleshoot --time "Convert UTC timestamps to local time"
/analyze --time "Show server logs from 14:00-15:00 UTC in PST"

# Performance monitoring windows
/analyze --time --performance "Peak hours analysis across regions"

# Maintenance windows
/task --time "Plan maintenance for lowest global impact"
```

**Integration Patterns**
```bash
# Time + Memory for scheduling
/task --time --memory "Remember team standup is at 10 AM EST daily"

# Time + Sequential for planning
/analyze --time --seq "Plan 24-hour deployment rollout across regions"

# Time + Fetch for event tracking
/analyze --time --fetch "https://calendar.api/events" "Convert event times to local"

# Time + MongoDB for timestamp operations
/analyze --time --mongodb-localhost "Query logs from last 24 hours in PST"
```

**Business Hours Calculations**
```bash
# Check business hours
/analyze --time "Is it business hours in Tokyo?"
/analyze --time "When does London office open in my timezone?"

# SLA calculations
/analyze --time "Calculate SLA deadline: reported at 15:00 PST, 4-hour SLA"

# Trading hours
/analyze --time "Show NYSE, LSE, and TSE trading hours in UTC"

# Support coverage
/analyze --time "Show 24/7 support coverage with 3 global offices"
```

**Date & Time Formatting**
```bash
# Standard time queries
/analyze --time "Current time in ISO 8601 format"
/analyze --time "Show epoch timestamp"

# Relative time calculations
/analyze --time "What time will it be in Tokyo in 3 hours?"
/analyze --time "Convert 'next Monday 10 AM EST' to UTC"

# Duration calculations
/analyze --time "How many hours between 9 AM PST and 5 PM CET?"
```

**Common Use Cases**
```bash
# Remote team coordination
/task --time "Team member in Sydney starting work - what time in SF?"

# Customer communication
/analyze --time "Customer in London - appropriate time to call from NYC?"

# Deployment planning
/deploy --time "Rolling deployment: start 00:00 UTC, show local times"

# Incident response
/troubleshoot --time "Incident reported at 14:30 JST - timeline in EST"

# Event scheduling
/task --time "Webinar at 2 PM EST - show times for all regions"
```

**Advanced Patterns**
```bash
# Daylight saving time handling
/analyze --time "When does DST change in US and EU this year?"
/analyze --time "Schedule meeting for March 15 - watch for DST changes"

# Holiday considerations
/analyze --time --memory "Store that Japan office is closed for Golden Week"

# On-call rotations
/task --time "Plan on-call schedule across PST, EST, and CET teams"

# Release trains
/deploy --time "Coordinate release train: Dev PST → QA IST → Prod SGT"
```

**Automation Examples**
```bash
# Cron job conversion
/analyze --time "Convert '0 2 * * *' from UTC to all office timezones"

# Scheduled tasks
/task --time "Run backup at 3 AM local time in each region"

# Time-based triggers
/build --time "Implement scheduler that respects local business hours"

# Alert scheduling
/analyze --time "Configure alerts for business hours only per region"
```

**Best Practices**

1. **Always Use IANA Timezones**
   ```bash
   # Good: IANA timezone
   /analyze --time "Time in America/New_York"
   
   # Avoid: Abbreviations (ambiguous)
   # PST could mean Pacific Standard or Philippine Standard
   ```

2. **Be Explicit About Conversions**
   ```bash
   # Good: Clear source and target
   /analyze --time "Convert 14:00 from Europe/London to Asia/Tokyo"
   
   # Less clear: Ambiguous request
   /analyze --time "Convert 2 PM to Tokyo time"
   ```

3. **Consider Daylight Saving Time**
   ```bash
   # Account for DST changes
   /analyze --time "Schedule for May 1st 10 AM EST (check DST status)"
   ```

4. **Use 24-Hour Format**
   ```bash
   # Preferred: 24-hour format
   /analyze --time "Convert 15:30 UTC to America/Chicago"
   
   # Also works: 12-hour with AM/PM
   /analyze --time "Convert 3:30 PM UTC to America/Chicago"
   ```

**Common Timezone Patterns**
```bash
# US mainland coverage
/analyze --time "Show current time in EST, CST, MST, PST"

# Major tech hubs
/analyze --time "Current time in SF, NYC, London, Bangalore, Singapore"

# Follow-the-sun offices
/analyze --time "Business hours overlap between SF, Dublin, and Sydney"

# Global all-hands timing
/analyze --time "Find time slot visible to US, EU, and APAC teams"
```

**Tips for Success**
- Use IANA timezone database names for accuracy
- Always specify source timezone for conversions
- Consider DST when scheduling future events
- Use 24-hour format to avoid AM/PM confusion
- Store timezone preferences with --memory
- Combine with other tools for complex scheduling
- Check business hours before scheduling meetings
- Account for holidays in different regions

### Mermaid (Diagram Generation)

**Overview**
Mermaid is a powerful diagram generation server that converts text descriptions into visual diagrams. It supports flowcharts, sequence diagrams, class diagrams, state diagrams, ERDs, Gantt charts, and more, with customizable themes and output formats.

**Installation**
```bash
# Install Mermaid MCP server
claude mcp add mermaid --
```

**Basic Diagram Generation**
```bash
# Simple flowchart
/document --mermaid "Create a flowchart showing user login process"

# Generate as PNG image
/design --mermaid "flowchart TD
    A[Start] --> B[Enter Credentials]
    B --> C{Valid?}
    C -->|Yes| D[Login Success]
    C -->|No| E[Show Error]
    E --> B"

# Generate as SVG (scalable)
/design --mermaid --svg "Create architecture diagram"
```

**Flowcharts & Process Diagrams**
```bash
# Software development process
/document --mermaid "flowchart LR
    A[Requirements] --> B[Design]
    B --> C[Development]
    C --> D[Testing]
    D --> E{Pass?}
    E -->|Yes| F[Deploy]
    E -->|No| C
    F --> G[Monitor]"

# Decision flowchart
/design --mermaid "flowchart TD
    Start([User Request]) --> Auth{Authenticated?}
    Auth -->|Yes| CheckRole{Admin?}
    Auth -->|No| Login[Redirect to Login]
    CheckRole -->|Yes| AdminDash[Admin Dashboard]
    CheckRole -->|No| UserDash[User Dashboard]
    Login --> End([End])"

# CI/CD pipeline
/document --mermaid --theme dark "flowchart LR
    A[Git Push] --> B[Build]
    B --> C[Unit Tests]
    C --> D[Integration Tests]
    D --> E{All Pass?}
    E -->|Yes| F[Deploy to Staging]
    E -->|No| G[Notify Developer]
    F --> H[E2E Tests]
    H --> I[Deploy to Production]"
```

**Sequence Diagrams**
```bash
# API interaction sequence
/document --mermaid "sequenceDiagram
    participant U as User
    participant F as Frontend
    participant A as API
    participant D as Database
    
    U->>F: Click Login
    F->>A: POST /auth/login
    A->>D: Query user
    D-->>A: User data
    A-->>F: JWT token
    F-->>U: Dashboard"

# Microservices communication
/design --mermaid --theme forest "sequenceDiagram
    participant Client
    participant Gateway
    participant AuthService
    participant UserService
    participant OrderService
    
    Client->>Gateway: Request Order
    Gateway->>AuthService: Validate Token
    AuthService-->>Gateway: Token Valid
    Gateway->>UserService: Get User Info
    Gateway->>OrderService: Create Order
    OrderService-->>Gateway: Order Created
    Gateway-->>Client: Order Response"
```

**Class Diagrams (Architecture)**
```bash
# Domain model
/design --mermaid --ddd "classDiagram
    class User {
        +String id
        +String email
        +String name
        +login()
        +logout()
    }
    class Order {
        +String id
        +Date created
        +OrderStatus status
        +calculateTotal()
    }
    class Product {
        +String id
        +String name
        +Decimal price
        +checkStock()
    }
    User '1' --> '*' Order : places
    Order '*' --> '*' Product : contains"

# Design patterns
/document --mermaid "classDiagram
    class Subject {
        <<interface>>
        +attach(Observer)
        +detach(Observer)
        +notify()
    }
    class Observer {
        <<interface>>
        +update()
    }
    class ConcreteSubject {
        -state
        +getState()
        +setState()
    }
    class ConcreteObserver {
        -subject
        +update()
    }
    Subject <|.. ConcreteSubject
    Observer <|.. ConcreteObserver
    ConcreteSubject --> Observer : notifies"
```

**State Diagrams**
```bash
# Order lifecycle
/design --mermaid "stateDiagram-v2
    [*] --> Pending
    Pending --> Processing : Payment Received
    Processing --> Shipped : Items Packed
    Processing --> Cancelled : Cancel Request
    Shipped --> Delivered : Package Received
    Shipped --> Returned : Return Request
    Delivered --> [*]
    Cancelled --> [*]
    Returned --> Refunded
    Refunded --> [*]"

# Authentication states
/document --mermaid "stateDiagram-v2
    [*] --> Unauthenticated
    Unauthenticated --> Authenticating : Login
    Authenticating --> Authenticated : Success
    Authenticating --> Unauthenticated : Failure
    Authenticated --> Unauthenticated : Logout
    Authenticated --> SessionExpired : Timeout
    SessionExpired --> Unauthenticated : Redirect"
```

**Entity Relationship Diagrams**
```bash
# Database schema
/design --mermaid --mongodb-localhost "erDiagram
    USER ||--o{ ORDER : places
    USER {
        string id PK
        string email UK
        string name
        datetime created
    }
    ORDER ||--|{ ORDER_ITEM : contains
    ORDER {
        string id PK
        string userId FK
        datetime orderDate
        string status
    }
    PRODUCT ||--o{ ORDER_ITEM : ordered
    PRODUCT {
        string id PK
        string name
        decimal price
        int stock
    }"

# Relational database design
/document --mermaid "erDiagram
    CUSTOMER ||--o{ ADDRESS : has
    CUSTOMER ||--o{ PAYMENT_METHOD : has
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE_ITEM : contains
    PRODUCT ||--o{ LINE_ITEM : 'ordered in'
    CATEGORY ||--o{ PRODUCT : contains
    SUPPLIER ||--o{ PRODUCT : supplies"
```

**Gantt Charts (Project Planning)**
```bash
# Development timeline
/task --mermaid "gantt
    title Project Development Timeline
    dateFormat YYYY-MM-DD
    section Planning
    Requirements    :done,    des1, 2024-01-01, 2024-01-07
    Design          :active,  des2, 2024-01-08, 10d
    section Development
    Backend API     :         des3, after des2, 20d
    Frontend        :         des4, after des2, 25d
    section Testing
    Unit Tests      :         des5, after des3, 5d
    Integration     :         des6, after des4, 7d
    section Deployment
    Staging         :         des7, after des6, 3d
    Production      :         des8, after des7, 2d"

# Sprint planning
/task --mermaid --time "gantt
    title Sprint 23 Timeline
    dateFormat YYYY-MM-DD
    section Sprint 23
    Sprint Planning     :done, 2024-01-15, 1d
    User Auth Feature   :active, 2024-01-16, 3d
    API Development     :active, 2024-01-16, 4d
    Testing             :2024-01-20, 2d
    Code Review         :2024-01-22, 1d
    Sprint Review       :2024-01-23, 1d"
```

**Pie Charts**
```bash
# Code coverage
/analyze --mermaid "pie title Code Coverage
    'Covered' : 85
    'Uncovered' : 15"

# Technology stack distribution
/analyze --mermaid "pie title Tech Stack
    'TypeScript' : 45
    'React' : 25
    'Node.js' : 20
    'Other' : 10"
```

**Git Graphs**
```bash
# Branching strategy
/document --mermaid "gitGraph
    commit
    branch develop
    checkout develop
    commit
    branch feature/auth
    checkout feature/auth
    commit
    commit
    checkout develop
    merge feature/auth
    checkout main
    merge develop
    commit tag: 'v1.0.0'"
```

**Advanced Features**
```bash
# Custom themes
/design --mermaid --theme dark "flowchart TD..."
/design --mermaid --theme forest "sequenceDiagram..."
/design --mermaid --theme neutral "classDiagram..."

# Background colors
/document --mermaid --background "#f0f0f0" "stateDiagram..."

# High-resolution PNG
/design --mermaid --png --width 2000 --height 1500 "erDiagram..."

# Save to file
/document --mermaid --save "architecture.png" "flowchart..."
```

**Integration Examples**
```bash
# Mermaid + Sequential for complex diagrams
/design --mermaid --seq "Create comprehensive system architecture diagram"

# Mermaid + Memory for documentation
/document --mermaid --memory "Generate and store project diagrams"

# Mermaid + DDD for domain modeling
/design --mermaid --ddd "Create domain model class diagram"

# Mermaid + Human Review for documentation
/document --mermaid --human-review "Generate diagrams for technical specification"
```

**Documentation Workflows**
```bash
# Architecture documentation
/document --mermaid --arch "Generate system architecture diagrams"
# Creates: flowchart, component diagram, deployment diagram

# API documentation
/document --mermaid --api "Create API interaction diagrams"
# Generates: sequence diagrams, state diagrams

# Database documentation
/design --mermaid --mongodb-localhost "Document database schema"
# Creates: ERD, relationship diagrams

# Process documentation
/document --mermaid --process "Document business processes"
# Generates: flowcharts, activity diagrams
```

**Common Use Cases**
```bash
# System architecture overview
/design --mermaid "Create microservices architecture diagram"

# User journey mapping
/document --mermaid "Map user onboarding journey"

# Database schema visualization
/design --mermaid "Visualize e-commerce database schema"

# Deployment pipeline
/document --mermaid "Illustrate CI/CD pipeline"

# State machine documentation
/design --mermaid "Document order processing states"
```

**Best Practices**

1. **Choose Appropriate Diagram Type**
   ```bash
   # Flowchart: Process flows, decisions
   # Sequence: Time-based interactions
   # Class: Structure, relationships
   # State: Lifecycle, transitions
   # ERD: Database schemas
   # Gantt: Timeline, scheduling
   ```

2. **Use Clear Naming**
   ```bash
   # Good: Descriptive node names
   /design --mermaid "flowchart TD
       UserLogin[User Enters Credentials]
       ValidateAuth{Validate Authentication}"
   
   # Avoid: Cryptic abbreviations
   ```

3. **Theme Selection**
   ```bash
   # Light backgrounds: default, neutral
   # Dark backgrounds: dark, forest
   # Match your documentation style
   ```

4. **Output Format**
   ```bash
   # PNG: Fixed size, screenshots
   # SVG: Scalable, interactive
   # Choose based on usage
   ```

**Tips for Success**
- Start simple and add complexity gradually
- Use consistent styling across diagrams
- Choose themes that match your documentation
- Use SVG for diagrams that need to scale
- Use PNG for fixed-size requirements
- Combine with other tools for comprehensive docs
- Save important diagrams with --save
- Use meaningful node and edge labels

### Helm (Kubernetes Package Management)

**Overview**
Helm is the package manager for Kubernetes, enabling you to deploy, manage, and version applications. The MCP server provides access to chart management, repository operations, and deployment workflows.

**Core Concepts**
- **Charts**: Packages containing Kubernetes resource definitions
- **Repositories**: Collections of charts (Bitnami, Elastic, etc.)
- **Releases**: Deployed instances of charts
- **Values**: Configuration parameters for charts

**Installation**
```bash
# Install Helm MCP server
claude mcp add helm --

# Verify server is running
# The server provides access to Helm CLI operations
```

**Repository Management**
```bash
# List configured repositories
/analyze --helm "List all Helm repositories"

# Add common repositories
/build --helm "Add Bitnami Helm repository"
/build --helm "Add Elastic Helm repository for Elasticsearch"
/build --helm "Add Prometheus community repository"

# Search repositories
/analyze --helm "Search for Redis charts in all repositories"
/analyze --helm "Find PostgreSQL charts with high availability support"
/analyze --helm "List all monitoring-related charts"

# Update repository index
/migrate --helm "Update all Helm repository indexes"
```

**Chart Discovery & Analysis**
```bash
# Browse available charts
/analyze --helm "Show all available charts from Bitnami"
/analyze --helm "List database charts with their latest versions"
/analyze --helm "Find charts for web applications"

# Chart details
/analyze --helm "Show details for bitnami/postgresql chart"
/analyze --helm "Get all configurable values for elastic/elasticsearch"
/analyze --helm "Show dependencies for prometheus/kube-prometheus-stack"

# Version information
/analyze --helm "List all versions of bitnami/redis"
/analyze --helm "Compare versions 14.x and 15.x of bitnami/postgresql"
```

**Chart Installation & Management**
```bash
# Generate installation commands
/build --helm "Generate Helm install command for PostgreSQL with custom values"
/build --helm "Create Redis deployment with persistence and authentication"
/build --helm "Deploy Elasticsearch cluster with 3 nodes"

# Custom values files
/build --helm "Create values.yaml for PostgreSQL with high availability"
/build --helm "Generate production-ready values for Redis Sentinel"
/build --helm "Create multi-environment values files for nginx"

# Upgrade strategies
/migrate --helm "Plan upgrade from PostgreSQL 14 to 15"
/migrate --helm "Create rolling update strategy for Elasticsearch"
/migrate --helm "Generate safe upgrade path for Prometheus stack"
```

**Common Application Deployments**
```bash
# Databases
/build --helm "Deploy PostgreSQL with replication and backups"
/build --helm "Install MongoDB replica set with authentication"
/build --helm "Set up Redis cluster with Sentinel"

# Web Applications
/build --helm "Deploy WordPress with MySQL and ingress"
/build --helm "Install GitLab with runners and registry"
/build --helm "Set up Nextcloud with PostgreSQL backend"

# Monitoring & Logging
/build --helm "Deploy full Prometheus monitoring stack"
/build --helm "Install ELK stack for centralized logging"
/build --helm "Set up Grafana with datasources"

# Message Queues
/build --helm "Deploy RabbitMQ with clustering"
/build --helm "Install Kafka with Zookeeper"
/build --helm "Set up NATS with streaming"
```

**Production Configurations**
```bash
# High Availability
/design --helm "Design HA PostgreSQL deployment with automatic failover"
/design --helm "Create Redis Sentinel configuration for production"
/design --helm "Plan Elasticsearch cluster with dedicated masters"

# Security
/improve --helm --security "Harden PostgreSQL deployment with network policies"
/improve --helm --security "Add TLS encryption to Redis cluster"
/improve --helm --security "Implement RBAC for monitoring stack"

# Resource Management
/improve --helm --performance "Optimize resource requests for PostgreSQL"
/improve --helm "Add HPA and VPA to web application"
/improve --helm "Configure pod disruption budgets"
```

**Troubleshooting & Maintenance**
```bash
# Debug deployments
/troubleshoot --helm "Debug failed PostgreSQL installation"
/troubleshoot --helm "Analyze CrashLoopBackOff in Elasticsearch pods"
/troubleshoot --helm "Fix pending PVC issues"

# Health checks
/analyze --helm "Verify PostgreSQL cluster health"
/analyze --helm "Check Redis Sentinel configuration"
/analyze --helm "Validate ingress controller setup"

# Backup & Recovery
/build --helm "Create backup strategy for PostgreSQL using charts"
/build --helm "Implement disaster recovery for Redis"
/build --helm "Set up automated snapshots for Elasticsearch"
```

**Integration Patterns**
```bash
# With CI/CD
/build --helm --git "Create GitOps workflow for Helm deployments"
/build --helm "Generate Jenkinsfile for Helm chart testing"
/build --helm "Create GitHub Actions for chart releases"

# With other MCP servers
/analyze --helm --seq "Design microservices deployment strategy"
/build --helm --magic "Create Kubernetes dashboard for Helm releases"
/document --helm --mermaid "Generate architecture diagram for Helm deployments"

# Multi-environment
/design --helm "Create environment-specific values structure"
/build --helm "Generate Kustomization overlays for Helm charts"
/migrate --helm "Plan blue-green deployment strategy"
```

**Best Practices**
```bash
# Chart Development
/build --helm "Create custom Helm chart for Node.js application"
/build --helm "Add tests to Helm chart"
/document --helm "Generate chart documentation"

# Values Management
/improve --helm "Refactor values.yaml for better organization"
/build --helm "Create values schema for validation"
/analyze --helm "Audit values for security issues"

# Version Control
/git --helm "Set up chart repository with versioning"
/build --helm "Create chart release automation"
/document --helm "Generate changelog for chart updates"
```

**Common Helm Repositories**
- **Bitnami**: Production-ready charts for popular applications
- **Elastic**: Official charts for Elastic Stack
- **Prometheus Community**: Monitoring and alerting charts
- **Grafana**: Visualization and dashboards
- **Ingress NGINX**: Ingress controller charts
- **Cert Manager**: TLS certificate management
- **Harbor**: Container registry charts
- **Argo**: GitOps and CD charts

**Tips for Success**
- Always check chart documentation for specific requirements
- Use `--dry-run` to preview changes before applying
- Maintain separate values files for different environments
- Regular repository updates ensure latest chart versions
- Test upgrades in staging before production
- Use chart dependencies wisely
- Implement proper RBAC for Helm operations
- Consider using Helm hooks for complex deployments
- Monitor chart deprecations and migration paths

### ArgoCD (GitOps Continuous Delivery)

**Overview**
ArgoCD is a declarative, GitOps continuous delivery tool for Kubernetes. The MCP server enables AI assistants to interact with ArgoCD applications, sync operations, and deployment workflows through natural language.

**Core Concepts**
- **Applications**: Kubernetes resources deployed by ArgoCD
- **Projects**: Logical grouping of applications
- **Sync**: Deploying changes from Git to Kubernetes
- **Health**: Application resource health status
- **Diff**: Comparison between Git and live state

**Installation**
```bash
# Install ArgoCD MCP server with credentials
claude mcp add argocd -- ARGOCD_BASE_URL="https://your-argocd.example.com" ARGOCD_API_TOKEN="your-api-token" npx -y argocd-mcp@latest stdio

# Get API token from ArgoCD UI:
# Settings → Account → Generate Token
```

**Application Management**
```bash
# List applications
/analyze --argocd "List all ArgoCD applications"
/analyze --argocd "Show applications in production namespace"
/analyze --argocd "Find applications that are out of sync"

# Application details
/analyze --argocd "Show details for my-app application"
/analyze --argocd "Get sync status for frontend application"
/analyze --argocd "Check health status of backend services"

# Application resources
/analyze --argocd "List all resources for payment-service"
/analyze --argocd "Show pods in the e-commerce application"
/analyze --argocd "Get deployment status for api-gateway"
```

**Sync Operations**
```bash
# Sync applications
/deploy --argocd "Sync the production-frontend application"
/deploy --argocd "Sync all applications in staging project"
/deploy --argocd "Hard refresh and sync backend-api"

# Selective sync
/deploy --argocd "Sync only the ConfigMap resources in my-app"
/deploy --argocd "Sync database deployment without migrations"
/deploy --argocd "Prune resources and sync auth-service"

# Rollback operations
/migrate --argocd "Rollback payment-service to previous version"
/migrate --argocd "Revert frontend to last known good state"
/troubleshoot --argocd "Roll back failed deployment of api-gateway"
```

**Health & Status Monitoring**
```bash
# Health checks
/analyze --argocd "Check health of all production applications"
/troubleshoot --argocd "Find unhealthy resources in my-app"
/analyze --argocd "Show degraded services in the cluster"

# Sync status
/analyze --argocd "Find all out-of-sync applications"
/analyze --argocd "Show applications with sync errors"
/troubleshoot --argocd "Debug sync failure for backend-service"

# Resource status
/analyze --argocd "Show pod status for frontend application"
/troubleshoot --argocd "Check why database deployment is pending"
/analyze --argocd "List failing hooks in migration-job"
```

**Diff & Preview**
```bash
# Preview changes
/analyze --argocd "Show diff for frontend application"
/analyze --argocd "Preview what would change if I sync backend"
/review --argocd "Compare Git vs live state for auth-service"

# Detailed diffs
/analyze --argocd "Show detailed YAML diff for ConfigMaps in my-app"
/review --argocd "List all resources that would be created on sync"
/analyze --argocd "Show what resources would be pruned"
```

**Project Management**
```bash
# List projects
/analyze --argocd "List all ArgoCD projects"
/analyze --argocd "Show applications in production project"
/analyze --argocd "Find projects with cluster access"

# Project details
/analyze --argocd "Show allowed repositories for dev project"
/analyze --argocd "List namespace restrictions for staging project"
/analyze --argocd "Check RBAC policies for production project"
```

**Multi-Environment Workflows**
```bash
# Environment promotion
/deploy --argocd "Promote frontend from staging to production"
/migrate --argocd "Copy application settings from dev to staging"
/design --argocd "Plan progressive rollout strategy"

# Environment comparison
/analyze --argocd "Compare frontend versions across environments"
/review --argocd "Show configuration differences between staging and prod"
/analyze --argocd "List image versions for all environments"

# Batch operations
/deploy --argocd "Sync all staging applications"
/analyze --argocd "Check health across all environments"
/migrate --argocd "Update image tags for all microservices"
```

**Troubleshooting & Debugging**
```bash
# Sync failures
/troubleshoot --argocd "Debug sync error for payment-service"
/troubleshoot --argocd "Find why frontend is stuck syncing"
/troubleshoot --argocd "Analyze hook failures in database migration"

# Resource issues
/troubleshoot --argocd "Why are pods not starting in my-app"
/troubleshoot --argocd "Debug CrashLoopBackOff in api-gateway"
/troubleshoot --argocd "Find resource quota issues"

# Configuration problems
/troubleshoot --argocd "Check for invalid YAML in application"
/troubleshoot --argocd "Validate Helm values for backend"
/troubleshoot --argocd "Find missing secrets or configmaps"
```

**Integration with CI/CD**
```bash
# GitHub Actions integration
/build --argocd --git "Create GitHub workflow for ArgoCD sync"
/build --argocd "Generate PR-based preview environments"
/design --argocd "Plan GitOps workflow with automatic sync"

# Jenkins integration
/build --argocd "Create Jenkins pipeline for ArgoCD deployment"
/build --argocd "Add sync stage to existing pipeline"
/design --argocd "Implement blue-green deployment with ArgoCD"

# GitLab CI integration
/build --argocd "Create GitLab CI job for ArgoCD operations"
/build --argocd "Implement merge request previews"
/design --argocd "Set up progressive delivery pipeline"
```

**Advanced Patterns**
```bash
# Progressive delivery
/design --argocd "Implement canary deployment for frontend"
/build --argocd "Create blue-green strategy for api"
/design --argocd "Plan feature flag integration with ArgoCD"

# Multi-cluster deployments
/design --argocd "Design multi-region deployment strategy"
/deploy --argocd "Sync application to disaster recovery cluster"
/analyze --argocd "Compare application state across clusters"

# App of Apps pattern
/build --argocd "Create app-of-apps for microservices"
/design --argocd "Implement hierarchical application structure"
/deploy --argocd "Bootstrap entire environment with one app"
```

**Security & Compliance**
```bash
# RBAC and permissions
/analyze --argocd --security "Audit RBAC policies for all projects"
/improve --argocd --security "Restrict deployment permissions"
/analyze --argocd "Show who can sync production apps"

# Policy enforcement
/build --argocd "Add OPA policies for deployments"
/analyze --argocd "Check compliance with security policies"
/improve --argocd --security "Enforce image scanning before sync"

# Secret management
/analyze --argocd "Find applications using external secrets"
/build --argocd "Integrate with HashiCorp Vault"
/improve --argocd --security "Implement sealed secrets"
```

**Integration with Other Tools**
```bash
# With Helm
/analyze --argocd --helm "Show Helm applications in ArgoCD"
/build --argocd --helm "Create Helm-based ArgoCD application"
/troubleshoot --argocd --helm "Debug Helm value overrides"

# With monitoring
/analyze --argocd "Export sync metrics to Prometheus"
/build --argocd "Create Grafana dashboard for ArgoCD"
/design --argocd "Plan alerting strategy for failed syncs"

# With other MCP servers
/analyze --argocd --seq "Design deployment strategy for microservices"
/document --argocd --mermaid "Create deployment flow diagram"
/troubleshoot --argocd --c7 "Research ArgoCD error messages"
```

**Best Practices**
```bash
# Application structure
/design --argocd "Structure applications for large teams"
/improve --argocd "Optimize sync performance"
/document --argocd "Create naming conventions for apps"

# Git repository organization
/design --argocd "Plan mono-repo vs multi-repo strategy"
/build --argocd "Set up environment-specific overlays"
/document --argocd "Create GitOps best practices guide"

# Automation
/build --argocd "Automate application creation"
/build --argocd "Create self-service deployment portal"
/design --argocd "Implement automated rollback on failures"
```

**Common Patterns**
- **Sync Waves**: Deploy resources in specific order
- **Sync Hooks**: Run jobs before/after sync
- **Resource Hooks**: Lifecycle management
- **Ignore Differences**: Handle dynamic fields
- **Custom Health**: Define health for CRDs
- **Automated Sync**: GitOps automation
- **Self Healing**: Automatic drift correction
- **Notifications**: Slack/email alerts

**Tips for Success**
- Use projects to organize applications logically
- Implement proper RBAC from the start
- Monitor sync performance and optimize large apps
- Use sync waves for complex dependencies
- Implement health checks for custom resources
- Regular cleanup of orphaned resources
- Use app-of-apps for environment bootstrapping
- Integrate with existing CI/CD pipelines
- Plan for disaster recovery scenarios
- Document your GitOps workflows

### Jira (Issue Tracking & Project Management)

**Overview**
Jira is Atlassian's powerful issue tracking and project management tool. The MCP server enables natural language interactions with Jira projects, issues, comments, and workflows.

**Core Concepts**
- **Projects**: Container for issues and workflows
- **Issues**: Tasks, bugs, stories, epics
- **Comments**: Discussion and collaboration
- **Statuses**: Workflow states (To Do, In Progress, Done)
- **JQL**: Jira Query Language for advanced searches

**Installation**
```bash
# Install Jira MCP server with credentials
claude mcp add jira -- ATLASSIAN_SITE_NAME="your-site" ATLASSIAN_USER_EMAIL="your-email@example.com" ATLASSIAN_API_TOKEN="your-api-token" @aashari/mcp-server-atlassian-jira

# Get API token from:
# https://id.atlassian.com/manage-profile/security/api-tokens
```

**Project Management**
```bash
# List projects
/analyze --jira "List all Jira projects I have access to"
/analyze --jira "Show projects containing 'mobile' in the name"
/analyze --jira "Find recently updated projects"

# Project details
/analyze --jira "Get details for PROJECT-KEY project"
/analyze --jira "Show components in the WEB project"
/analyze --jira "List project metadata for MOBILE"

# Project analysis
/analyze --jira "Show issue distribution by type in DEV project"
/analyze --jira "Find projects with most open issues"
/review --jira "Analyze project health metrics"
```

**Issue Search & Management**
```bash
# Basic searches
/analyze --jira "Find all open issues in PROJECT-KEY"
/analyze --jira "Show my assigned issues"
/analyze --jira "List high priority bugs"

# Advanced JQL searches
/analyze --jira "Search issues with JQL: project = DEV AND status = 'In Progress' AND assignee = currentUser()"
/analyze --jira "Find issues: created >= -7d AND priority in (High, Highest)"
/analyze --jira "Show unresolved issues in current sprint"

# Multi-project searches
/analyze --jira "Find all critical bugs across all projects"
/analyze --jira "Show issues assigned to me in multiple projects"
/analyze --jira "List overdue issues company-wide"
```

**Issue Details & Updates**
```bash
# Get issue information
/analyze --jira "Show details for PROJ-123"
/analyze --jira "Get full issue information including development info for WEB-456"
/analyze --jira "Check status and assignee for MOBILE-789"

# Issue analysis
/analyze --jira "Show all subtasks for EPIC-100"
/analyze --jira "List linked issues for PROJ-123"
/analyze --jira "Get time tracking information for DEV-456"

# Bulk operations
/analyze --jira "Find all issues blocked by PROJ-123"
/analyze --jira "Show issues with similar descriptions"
/review --jira "Analyze duplicate issues in project"
```

**Comments & Collaboration**
```bash
# List comments
/analyze --jira "Show all comments for PROJ-123"
/analyze --jira "Get recent comments on WEB-456"
/analyze --jira "Find comments mentioning deployment"

# Add comments
/task --jira "Add comment to PROJ-123: Investigation complete, root cause identified"
/task --jira "Comment on WEB-456 with testing results"
/task --jira "Add implementation notes to DEV-789"

# Comment analysis
/analyze --jira "Find issues with no comments in last 7 days"
/analyze --jira "Show most discussed issues"
/review --jira "Analyze communication patterns in project"
```

**Workflow & Status Management**
```bash
# List statuses
/analyze --jira "Show all available statuses"
/analyze --jira "List workflow statuses for DEV project"
/analyze --jira "Find valid transitions for PROJ-123"

# Status analysis
/analyze --jira "Show issues stuck in 'In Review' for over 3 days"
/analyze --jira "Find bottlenecks in workflow"
/analyze --jira "List issues by status in PROJECT"

# Workflow insights
/analyze --jira "Calculate average time in each status"
/analyze --jira "Show workflow efficiency metrics"
/review --jira "Identify process improvements"
```

**Sprint & Agile Management**
```bash
# Sprint queries
/analyze --jira "Show current sprint issues"
/analyze --jira "Find incomplete issues from last sprint"
/analyze --jira "List sprint velocity trends"

# Sprint planning
/analyze --jira "Find unestimated issues in backlog"
/analyze --jira "Show issues ready for next sprint"
/estimate --jira "Analyze story point distribution"

# Sprint monitoring
/analyze --jira "Show sprint burndown data"
/analyze --jira "Find at-risk issues in current sprint"
/troubleshoot --jira "Identify sprint blockers"
```

**Team & Resource Management**
```bash
# Team workload
/analyze --jira "Show workload distribution across team"
/analyze --jira "Find overloaded team members"
/analyze --jira "List unassigned high-priority issues"

# Performance metrics
/analyze --jira "Show team velocity over last 5 sprints"
/analyze --jira "Calculate average resolution time by assignee"
/review --jira "Analyze team productivity metrics"

# Capacity planning
/analyze --jira "Estimate team capacity for next sprint"
/analyze --jira "Show historical capacity utilization"
/design --jira "Plan resource allocation"
```

**Integration Patterns**
```bash
# With Git/Development
/analyze --jira --git "Show issues with recent commits"
/build --jira --git "Create branch name from PROJ-123"
/git --jira "Link commit to Jira issue"

# With CI/CD
/deploy --jira "Update issue status after deployment"
/analyze --jira "Find issues ready for release"
/task --jira "Add deployment notes to issue"

# With other MCP servers
/analyze --jira --seq "Analyze issue resolution patterns"
/document --jira --mermaid "Create workflow diagram"
/troubleshoot --jira --c7 "Research Jira API error"
```

**Reporting & Analytics**
```bash
# Project reports
/document --jira "Generate project status report"
/analyze --jira "Create issue aging report"
/review --jira "Build team performance dashboard"

# Custom reports
/analyze --jira "Show issues by component and priority"
/analyze --jira "Generate SLA compliance report"
/document --jira "Create executive summary"

# Trend analysis
/analyze --jira "Show issue creation trends"
/analyze --jira "Analyze resolution time patterns"
/review --jira "Identify improvement opportunities"
```

**Best Practices**
```bash
# Issue hygiene
/analyze --jira "Find issues with missing information"
/improve --jira "Identify stale issues for cleanup"
/review --jira "Check issue naming conventions"

# Process optimization
/analyze --jira "Find workflow inefficiencies"
/design --jira "Optimize issue templates"
/improve --jira "Streamline status transitions"

# Documentation
/document --jira "Create team Jira guidelines"
/document --jira "Generate JQL query library"
/build --jira "Create issue template repository"
```

**Common JQL Patterns**
```bash
# Time-based queries
"created >= -7d"                    # Last 7 days
"updated >= startOfDay(-1)"         # Since yesterday
"due <= endOfWeek()"               # Due this week

# User queries
"assignee = currentUser()"          # Assigned to me
"reporter in membersOf('team')"     # Reported by team
"watcher = currentUser()"           # Watching issues

# Status queries
"status changed TO 'Done' AFTER -7d"  # Recently completed
"status NOT IN ('Done', 'Closed')"    # Open issues
"statusCategory = 'In Progress'"       # Active work

# Complex queries
"project = DEV AND priority >= High AND created >= -30d"
"labels in ('bug', 'critical') AND resolution is EMPTY"
"fixVersion in unreleasedVersions() AND status = 'Done'"
```

**Tips for Success**
- Use meaningful issue titles and descriptions
- Keep issues updated with current status
- Add comments for important decisions
- Link related issues appropriately
- Use labels and components consistently
- Regular backlog grooming
- Monitor cycle time and lead time
- Automate repetitive tasks
- Integrate with development workflow
- Create saved JQL filters for common searches

### Confluence (Wiki & Documentation Platform)

**Overview**
Confluence is Atlassian's collaborative wiki and documentation platform. The MCP server enables natural language interactions with Confluence spaces, pages, comments, and search functionality.

**Core Concepts**
- **Spaces**: Container for related pages and content
- **Pages**: Individual documents with rich content
- **Comments**: Discussion threads on pages
- **CQL**: Confluence Query Language for advanced searches
- **Labels**: Tags for organizing content

**Installation**
```bash
# Install Confluence MCP server with credentials
claude mcp add confluence -- ATLASSIAN_SITE_NAME="your-site" ATLASSIAN_USER_EMAIL="your-email@example.com" ATLASSIAN_API_TOKEN="your-api-token" @aashari/mcp-server-atlassian-confluence

# Get API token from:
# https://id.atlassian.com/manage-profile/security/api-tokens
```

**Space Management**
```bash
# List spaces
/analyze --confluence "List all Confluence spaces"
/analyze --confluence "Show global spaces only"
/analyze --confluence "Find personal spaces"

# Space details
/analyze --confluence "Get details for DEV space"
/analyze --confluence "Show content structure of DOCS space"
/analyze --confluence "List permissions for PROJECT space"

# Space analysis
/analyze --confluence "Find most active spaces"
/analyze --confluence "Show spaces with recent updates"
/review --confluence "Analyze space usage patterns"
```

**Page Discovery & Reading**
```bash
# List pages
/analyze --confluence "List all pages in DEV space"
/analyze --confluence "Find pages with title containing 'API'"
/analyze --confluence "Show recently updated pages"

# Page content
/analyze --confluence "Get content of page ID 12345678"
/analyze --confluence "Show page content in markdown format"
/analyze --confluence "Read installation guide page"

# Page hierarchy
/analyze --confluence "Show page tree for DOCS space"
/analyze --confluence "Find child pages of Architecture page"
/analyze --confluence "List parent pages up to space home"
```

**Search Operations**
```bash
# Basic search
/analyze --confluence "Search for 'authentication' across all spaces"
/analyze --confluence "Find pages about database migration"
/analyze --confluence "Search for deployment procedures"

# CQL searches
/analyze --confluence "Search with CQL: space = DEV AND label = security"
/analyze --confluence "Find pages: type = page AND lastmodified > -7d"
/analyze --confluence "Search: creator = currentUser() AND label in (draft, review)"

# Advanced search
/analyze --confluence "Find pages with specific labels in DEV space"
/analyze --confluence "Search blog posts about releases"
/analyze --confluence "Find attachments named 'diagram'"
```

**Documentation Workflows**
```bash
# Technical documentation
/document --confluence "Create API documentation structure"
/analyze --confluence "Find existing API docs to update"
/review --confluence "Check documentation completeness"

# Knowledge base
/document --confluence "Design knowledge base hierarchy"
/analyze --confluence "Find FAQ pages that need updates"
/improve --confluence "Identify documentation gaps"

# Process documentation
/document --confluence "Create deployment process guide"
/analyze --confluence "Review onboarding documentation"
/build --confluence "Generate troubleshooting guides"
```

**Comments & Collaboration**
```bash
# List comments
/analyze --confluence "Show all comments on page 12345678"
/analyze --confluence "Find recent comments in DEV space"
/analyze --confluence "List unresolved comments"

# Comment analysis
/analyze --confluence "Find pages with active discussions"
/analyze --confluence "Show comment threads about bugs"
/review --confluence "Analyze collaboration patterns"

# Engagement metrics
/analyze --confluence "Show most commented pages"
/analyze --confluence "Find pages needing review based on comments"
/analyze --confluence "Track feedback on documentation"
```

**Content Organization**
```bash
# Labels and tags
/analyze --confluence "List all labels in DOCS space"
/analyze --confluence "Find pages with 'deprecated' label"
/analyze --confluence "Show label usage statistics"

# Content structure
/design --confluence "Plan documentation architecture"
/analyze --confluence "Review content hierarchy"
/improve --confluence "Optimize navigation structure"

# Content audit
/analyze --confluence "Find outdated pages (not updated in 6 months)"
/analyze --confluence "Identify orphaned pages"
/review --confluence "Audit content quality"
```

**Team Collaboration**
```bash
# Contributor analysis
/analyze --confluence "Show top contributors in DEV space"
/analyze --confluence "Find pages by specific author"
/analyze --confluence "List my recent contributions"

# Review workflows
/analyze --confluence "Find pages marked for review"
/analyze --confluence "Show pages pending approval"
/review --confluence "Track documentation review status"

# Team spaces
/analyze --confluence "List team-specific spaces"
/analyze --confluence "Show space permissions and access"
/design --confluence "Plan team workspace structure"
```

**Integration Patterns**
```bash
# With Jira
/analyze --confluence --jira "Link documentation to Jira issues"
/document --confluence --jira "Create release notes from Jira tickets"
/build --confluence --jira "Generate project documentation"

# With development
/document --confluence --git "Create deployment docs from README"
/analyze --confluence "Find API documentation to update"
/build --confluence "Generate changelog page"

# With other MCP servers
/document --confluence --mermaid "Add diagrams to documentation"
/analyze --confluence --seq "Plan documentation strategy"
/build --confluence --magic "Create documentation templates"
```

**Documentation Best Practices**
```bash
# Template management
/build --confluence "Create documentation templates"
/analyze --confluence "Find and standardize templates"
/improve --confluence "Optimize template usage"

# Style guides
/document --confluence "Create documentation style guide"
/analyze --confluence "Check adherence to style guide"
/review --confluence "Improve documentation consistency"

# Maintenance
/analyze --confluence "Find broken links in documentation"
/improve --confluence "Update outdated screenshots"
/cleanup --confluence "Archive obsolete documentation"
```

**Knowledge Management**
```bash
# Knowledge capture
/document --confluence "Create runbook template"
/build --confluence "Generate troubleshooting guide"
/analyze --confluence "Identify knowledge gaps"

# Knowledge sharing
/analyze --confluence "Find most viewed pages"
/improve --confluence "Enhance discoverability"
/design --confluence "Plan knowledge base structure"

# Knowledge retention
/analyze --confluence "Backup critical documentation"
/document --confluence "Create disaster recovery docs"
/build --confluence "Generate offline documentation"
```

**Advanced Search Patterns**
```bash
# CQL examples
"space = DEV AND type = page"              # All pages in DEV space
"label = 'api' AND created > -30d"         # New API docs
"text ~ 'security' AND space = DOCS"       # Security mentions
"ancestor = 12345678"                       # Child pages
"creator = 'john.doe' AND label = draft"   # User's drafts

# Content type searches
"type = blogpost AND created > -7d"        # Recent blog posts
"type = attachment AND title ~ '.pdf'"     # PDF attachments
"type = comment AND created = today"       # Today's comments

# Complex queries
"space in (DEV, DOCS) AND label in ('api', 'guide')"
"lastmodified > -30d AND creator != currentUser()"
"title ~ 'install*' OR label = 'installation'"
```

**Tips for Success**
- Use clear, descriptive page titles
- Maintain consistent page hierarchy
- Apply labels systematically
- Keep documentation up-to-date
- Use templates for consistency
- Link related pages appropriately
- Include diagrams and visuals
- Regular content reviews
- Archive outdated content
- Enable page watching for updates
- Use macros for dynamic content
- Implement review cycles
- Track documentation metrics

### Excel (Spreadsheet Operations)

**Overview**
Excel MCP server provides comprehensive Microsoft Excel file manipulation capabilities. Create, read, write, format spreadsheets, work with formulas, charts, pivot tables, and more through natural language commands.

**Core Concepts**
- **Workbooks**: Excel files containing worksheets
- **Worksheets**: Individual sheets within a workbook
- **Cells**: Individual data points (A1, B2, etc.)
- **Ranges**: Groups of cells (A1:D10)
- **Formulas**: Excel calculations and functions
- **Charts**: Visual data representations
- **Pivot Tables**: Data summarization tools

**Installation**
```bash
# Install Excel MCP server
claude mcp add excel -- uvx excel-mcp-server stdio
```

**Workbook Management**
```bash
# Create workbooks
/build --excel "Create new Excel workbook at reports/monthly.xlsx"
/build --excel "Create workbook with sheets: Summary, Data, Charts"
/build --excel "Create budget template workbook"

# Workbook metadata
/analyze --excel "Get metadata for sales_data.xlsx including all sheets"
/analyze --excel "Show sheet names and ranges in report.xlsx"
/analyze --excel "List all named ranges in workbook"

# Worksheet operations
/build --excel "Add new worksheet 'Q4 Results' to report.xlsx"
/task --excel "Copy worksheet 'Template' to 'January' in budget.xlsx"
/task --excel "Rename sheet 'Sheet1' to 'Dashboard' in metrics.xlsx"
/cleanup --excel "Delete unused worksheets from old_report.xlsx"
```

**Data Operations**
```bash
# Write data
/build --excel "Write sales data to Sheet1 starting at A1: [{product: 'Widget', sales: 100}, {product: 'Gadget', sales: 150}]"
/task --excel "Import CSV data into new worksheet 'Imports'"
/build --excel "Create employee roster with columns: Name, Department, Salary, Start Date"

# Read data
/analyze --excel "Read data from sales.xlsx Sheet1 range A1:F100"
/analyze --excel "Preview first 10 rows of customer data"
/analyze --excel "Extract all data from 'Inventory' sheet"

# Data validation
/analyze --excel "Show data validation rules in order_form.xlsx"
/improve --excel "Add dropdown list validation for Status column"
/build --excel "Create data entry form with validations"
```

**Formatting Operations**
```bash
# Cell formatting
/improve --excel "Format A1:A10 as bold with blue background in report.xlsx"
/improve --excel "Apply currency format to column D in budget.xlsx"
/improve --excel "Format header row with bold, centered, wrapped text"

# Conditional formatting
/improve --excel "Apply color scale to sales figures B2:B100"
/improve --excel "Highlight cells > 1000 in green, < 500 in red"
/improve --excel "Add data bars to performance metrics column"

# Merge operations
/task --excel "Merge cells A1:D1 for title in report.xlsx"
/task --excel "Create merged header sections for quarterly reports"
/analyze --excel "Show all merged cells in worksheet"
```

**Formula Operations**
```bash
# Basic formulas
/build --excel "Apply SUM formula to cell B10 for range B2:B9"
/build --excel "Add AVERAGE formula for monthly sales data"
/build --excel "Create percentage calculation in column E"

# Advanced formulas
/build --excel "Apply VLOOKUP formula to match product codes"
/build --excel "Create IF statement for pass/fail grades"
/build --excel "Add SUMIF formula for conditional totals"

# Formula validation
/analyze --excel "Validate formula syntax: =SUM(A1:A10)*1.1"
/troubleshoot --excel "Check why formula in D5 returns #REF error"
/analyze --excel "Find all cells with formulas in worksheet"
```

**Chart Creation**
```bash
# Basic charts
/build --excel "Create line chart from A1:B20 data at cell D5"
/build --excel "Generate bar chart for quarterly sales comparison"
/build --excel "Create pie chart showing market share data"

# Advanced charts
/build --excel "Create combination chart with bars and line"
/build --excel "Generate scatter plot for correlation analysis"
/build --excel "Build waterfall chart for financial data"

# Chart customization
/improve --excel "Add title 'Sales Trends 2024' to chart"
/improve --excel "Set axis labels: X='Month', Y='Revenue ($)'"
/improve --excel "Apply professional color scheme to charts"
```

**Pivot Table Operations**
```bash
# Create pivot tables
/build --excel "Create pivot table from sales data with Product in rows, Month in columns, sum of Sales as values"
/build --excel "Generate pivot analyzing expenses by department and category"
/build --excel "Build customer analysis pivot with region and product filters"

# Pivot table customization
/improve --excel "Add grand totals to pivot table"
/improve --excel "Sort pivot by total sales descending"
/improve --excel "Group dates by quarter in pivot table"

# Multiple aggregations
/build --excel "Create pivot with sum, average, and count for sales metrics"
/analyze --excel "Show top 10 products by revenue in pivot"
/improve --excel "Add calculated field for profit margin to pivot"
```

**Table Operations**
```bash
# Create Excel tables
/build --excel "Convert range A1:F100 to Excel table named 'SalesData'"
/build --excel "Create formatted table with alternating row colors"
/build --excel "Build filterable inventory table with sorting"

# Table management
/improve --excel "Add total row to sales table"
/improve --excel "Apply TableStyleMedium9 to data table"
/analyze --excel "List all tables in workbook with ranges"
```

**Advanced Workflows**
```bash
# Financial reporting
/build --excel "Create monthly financial report template with formulas"
/build --excel "Generate P&L statement with automatic calculations"
/design --excel "Build dashboard with KPI metrics and charts"

# Data analysis
/analyze --excel "Perform statistical analysis on dataset"
/build --excel "Create correlation matrix from variables"
/analyze --excel "Generate summary statistics table"

# Automation templates
/build --excel "Create invoice template with auto-calculations"
/build --excel "Build timesheet with overtime formulas"
/design --excel "Generate project tracker with Gantt chart"
```

**Integration Patterns**
```bash
# With databases
/build --excel --mongodb-localhost "Export MongoDB query results to Excel"
/analyze --excel "Import Excel data for database upload"
/migrate --excel "Sync Excel data with database tables"

# With visualization
/build --excel --mermaid "Create flowchart from Excel process data"
/document --excel "Generate documentation from Excel metadata"
/analyze --excel --seq "Plan data transformation pipeline"

# With other tools
/build --excel --magic "Create UI for Excel data entry"
/analyze --excel --jira "Export Jira issues to Excel report"
/document --excel --confluence "Create Excel guide in Confluence"
```

**Best Practices**
```bash
# File organization
/design --excel "Plan workbook structure for scalability"
/improve --excel "Optimize file size by removing unused data"
/cleanup --excel "Remove duplicate formulas and consolidate"

# Performance optimization
/improve --excel "Convert complex formulas to values where possible"
/analyze --excel "Identify slow-calculating formulas"
/improve --excel "Optimize pivot table source data"

# Error handling
/troubleshoot --excel "Find and fix circular references"
/analyze --excel "Check for broken external links"
/improve --excel "Add error handling to formulas"
```

**Common Patterns**
```bash
# Templates
/build --excel "Create reusable budget template"
/build --excel "Design expense report template"
/build --excel "Generate project planning template"

# Reports
/build --excel "Create automated sales report"
/build --excel "Generate monthly KPI dashboard"
/build --excel "Build executive summary report"

# Data processing
/build --excel "Create data cleaning workflow"
/analyze --excel "Validate imported data quality"
/improve --excel "Standardize data formats"
```

**Tips for Success**
- Use meaningful worksheet and range names
- Apply consistent formatting across workbooks
- Document complex formulas with comments
- Use tables for dynamic data ranges
- Implement data validation for accuracy
- Create templates for recurring tasks
- Use named ranges for clarity
- Keep formulas simple and readable
- Regular backup of important files
- Test formulas with sample data
- Use conditional formatting sparingly
- Organize data in tabular format
- Avoid merged cells in data ranges

### OpenAPI (API Specification Management)

**Overview**
OpenAPI MCP server loads and serves multiple OpenAPI specifications from your project's `specs/` directory. It enables LLM-powered IDE integrations to understand and work with your APIs, providing complete context about operations, schemas, and API structure.

**Core Concepts**
- **Specifications**: OpenAPI/Swagger files defining API contracts
- **Operations**: API endpoints with methods, parameters, responses
- **Schemas**: Data models and structures used by APIs
- **Catalog**: Indexed collection of all loaded specifications
- **Dereferencing**: Resolving $ref pointers for complete context

**Installation**
```bash
# Install OpenAPI MCP server pointing to specs directory
claude mcp add openapi -- npx -y @reapi/mcp-openapi@latest --dir ./specs

# The server will scan ./specs directory for OpenAPI files
```

**Catalog Management**
```bash
# Refresh catalog
/task --openapi "Refresh the API catalog to load new specifications"
/task --openapi "Reload catalog after adding new OpenAPI files"
/analyze --openapi "Check catalog refresh status"

# Get catalog overview
/analyze --openapi "Get complete API catalog with all specifications"
/analyze --openapi "Show summary of all loaded APIs"
/analyze --openapi "List all available API specifications"

# Catalog inspection
/analyze --openapi "Show total operations and schemas count"
/analyze --openapi "Find APIs with the most endpoints"
/analyze --openapi "List APIs by version"
```

**API Discovery & Search**
```bash
# Search operations
/analyze --openapi "Search for user-related operations"
/analyze --openapi "Find all POST operations across APIs"
/analyze --openapi "Search for authentication endpoints"

# Targeted search
/analyze --openapi "Search for payment operations in billing-api spec"
/analyze --openapi "Find CRUD operations for products in catalog-api"
/analyze --openapi "List all webhook endpoints"

# Schema search
/analyze --openapi "Search for User schema across all specs"
/analyze --openapi "Find all schemas with 'address' in the name"
/analyze --openapi "Search for error response schemas"
```

**Operation Analysis**
```bash
# Load by operationId
/analyze --openapi "Load operation createUser from user-api spec"
/analyze --openapi "Get details for updateProduct operation in catalog-api"
/analyze --openapi "Show operation getUserById with full context"

# Load by path and method
/analyze --openapi "Load POST /api/users from user-api spec"
/analyze --openapi "Get details for GET /products/{id} in catalog-api"
/analyze --openapi "Show DELETE /orders/{orderId} operation"

# Operation inspection
/analyze --openapi "Show request/response schemas for createOrder"
/analyze --openapi "List all parameters for searchProducts operation"
/analyze --openapi "Get security requirements for admin endpoints"
```

**Schema Analysis**
```bash
# Load schemas
/analyze --openapi "Load User schema from user-api spec"
/analyze --openapi "Get Product schema details from catalog-api"
/analyze --openapi "Show OrderResponse schema with all properties"

# Schema relationships
/analyze --openapi "Find all schemas that reference User"
/analyze --openapi "Show schema inheritance hierarchy"
/analyze --openapi "List all enum schemas"

# Schema validation
/analyze --openapi "Analyze required fields in Customer schema"
/analyze --openapi "Show validation rules for Payment schema"
/analyze --openapi "Find schemas with regex patterns"
```

**API Documentation**
```bash
# Generate documentation
/document --openapi "Create API overview documentation"
/document --openapi "Generate endpoint reference for user-api"
/document --openapi "Build schema documentation for all models"

# API guides
/document --openapi "Create authentication guide from spec"
/document --openapi "Generate pagination documentation"
/document --openapi "Build error handling guide"

# Integration docs
/document --openapi "Create quick start guide for developers"
/document --openapi "Generate SDK usage examples"
/document --openapi "Build webhook integration guide"
```

**Code Generation Support**
```bash
# Client generation
/build --openapi "Generate TypeScript types from schemas"
/build --openapi "Create API client for user-service"
/build --openapi "Generate React hooks for API operations"

# Server stubs
/build --openapi "Create Express route handlers from spec"
/build --openapi "Generate controller interfaces"
/build --openapi "Build validation middleware from schemas"

# Testing
/build --openapi "Generate API test cases from operations"
/build --openapi "Create mock server from specification"
/build --openapi "Build request/response examples"
```

**API Design & Review**
```bash
# Design validation
/review --openapi "Analyze API design consistency"
/review --openapi "Check RESTful conventions compliance"
/analyze --openapi "Find operations missing error responses"

# Security review
/review --openapi --security "Audit API security definitions"
/analyze --openapi "Find endpoints without authentication"
/review --openapi "Check for sensitive data in responses"

# Performance analysis
/analyze --openapi "Find operations with large payloads"
/review --openapi "Identify chatty API patterns"
/analyze --openapi "Check for N+1 query possibilities"
```

**Integration Patterns**
```bash
# With development
/build --openapi --typescript "Generate type-safe API client"
/analyze --openapi --git "Track API changes in version control"
/test --openapi "Validate implementation against spec"

# With documentation
/document --openapi --confluence "Publish API docs to Confluence"
/build --openapi --mermaid "Create API flow diagrams"
/document --openapi "Generate OpenAPI changelog"

# With testing
/test --openapi --playwright "Generate E2E tests from API spec"
/build --openapi "Create Postman collection"
/analyze --openapi "Generate curl examples"
```

**Specification Management**
```bash
# Version control
/analyze --openapi "Compare API versions for breaking changes"
/review --openapi "Show deprecated operations"
/migrate --openapi "Plan API version migration"

# Specification quality
/improve --openapi "Add missing operation descriptions"
/analyze --openapi "Find incomplete schema definitions"
/improve --openapi "Enhance error response documentation"

# Maintenance
/cleanup --openapi "Remove unused schema definitions"
/improve --openapi "Consolidate duplicate schemas"
/analyze --openapi "Validate specification syntax"
```

**Advanced Workflows**
```bash
# API gateway configuration
/build --openapi "Generate Kong API gateway config"
/build --openapi "Create AWS API Gateway definition"
/design --openapi "Plan rate limiting strategy"

# Microservices
/analyze --openapi "Map service dependencies from APIs"
/design --openapi "Plan service mesh configuration"
/build --openapi "Generate service contracts"

# GraphQL migration
/analyze --openapi "Identify candidates for GraphQL"
/design --openapi "Plan REST to GraphQL migration"
/build --openapi "Generate GraphQL schema from OpenAPI"
```

**Best Practices**
```bash
# Specification organization
/design --openapi "Structure multi-service API specs"
/improve --openapi "Implement specification modularity"
/document --openapi "Create spec maintenance guide"

# Naming conventions
/review --openapi "Check operation naming consistency"
/improve --openapi "Standardize schema property names"
/analyze --openapi "Validate path parameter formats"

# Documentation
/improve --openapi "Enhance operation descriptions"
/build --openapi "Add request/response examples"
/document --openapi "Create API style guide"
```

**Common Patterns**
```bash
# CRUD operations
/analyze --openapi "Show all CRUD patterns in APIs"
/build --openapi "Generate standard CRUD endpoints"
/review --openapi "Validate CRUD consistency"

# Pagination
/analyze --openapi "Find pagination patterns"
/improve --openapi "Standardize pagination approach"
/document --openapi "Create pagination guide"

# Error handling
/analyze --openapi "Review error response patterns"
/improve --openapi "Standardize error schemas"
/build --openapi "Generate error handling code"
```

**Tips for Success**
- Keep specifications in sync with implementation
- Use consistent naming conventions
- Document all parameters and responses
- Include examples for complex operations
- Version your APIs properly
- Use schema references to avoid duplication
- Implement comprehensive error responses
- Regular specification validation
- Monitor API usage patterns
- Plan for backward compatibility
- Use semantic versioning
- Automate spec generation where possible
- Test against specifications

### NixOS (Package & Configuration Search)

**Overview**
NixOS MCP server provides real-time access to the Nix ecosystem including 130K+ packages, 22K+ NixOS configuration options, 4K+ Home Manager settings, 1K+ nix-darwin configurations, and package version history. Search, explore, and get accurate information about the entire Nix ecosystem.

**Core Concepts**
- **Packages**: Software available in Nix repositories
- **Options**: Configuration settings for NixOS systems
- **Channels**: Release branches (stable, unstable)
- **Home Manager**: User-level configuration management
- **nix-darwin**: macOS-specific Nix configurations
- **Flakes**: Modern Nix packaging format
- **NixHub**: Package version history tracking

**Installation**
```bash
# Install NixOS MCP server
claude mcp add nixos -- nix run github:utensils/mcp-nixos --
```

**Package Search & Discovery**
```bash
# Search packages
/analyze --nixos "Search for python packages in nixpkgs"
/analyze --nixos "Find all nodejs versions available"
/analyze --nixos "Search for rust development tools"

# Package details
/analyze --nixos "Get info about firefox package"
/analyze --nixos "Show details for postgresql_15 package"
/analyze --nixos "Check if neovim package exists in stable channel"

# Channel-specific searches
/analyze --nixos "Search for docker in nixos-24.05 channel"
/analyze --nixos "Find kubernetes packages in unstable"
/analyze --nixos "List available channels"
```

**Configuration Options**
```bash
# NixOS options search
/analyze --nixos "Search for networking configuration options"
/analyze --nixos "Find all systemd service options"
/analyze --nixos "Search for security-related options"

# Option details
/analyze --nixos "Get info about services.nginx.enable option"
/analyze --nixos "Show details for boot.loader.grub options"
/analyze --nixos "Explain networking.firewall configuration"

# Statistics
/analyze --nixos "Show NixOS package and option statistics"
/analyze --nixos "Get counts for stable channel"
/analyze --nixos "Display total available packages"
```

**Version History & Discovery**
```bash
# Package version history
/analyze --nixos "Show version history for ruby package"
/analyze --nixos "Get last 10 versions of nodejs with commit hashes"
/analyze --nixos "Find postgresql version history"

# Find specific versions
/analyze --nixos "Find Ruby 2.6 in nixpkgs history"
/analyze --nixos "Search for Python 3.8.5 with commit hash"
/analyze --nixos "Locate old MySQL 5.7 version"

# Version analysis
/analyze --nixos "Compare nodejs versions across channels"
/analyze --nixos "Track firefox version evolution"
/analyze --nixos "Find when package was added to nixpkgs"
```

**Home Manager Configuration**
```bash
# Search Home Manager options
/analyze --nixos "Search Home Manager git configuration"
/analyze --nixos "Find Home Manager shell options"
/analyze --nixos "Search for Home Manager vim settings"

# Option categories
/analyze --nixos "List all Home Manager option categories"
/analyze --nixos "Show Home Manager statistics"
/analyze --nixos "Browse programs.* options in Home Manager"

# Detailed configuration
/analyze --nixos "Get info about programs.zsh options"
/analyze --nixos "Show home.packages configuration"
/analyze --nixos "Explain services.syncthing settings"
```

**macOS (nix-darwin) Configuration**
```bash
# Search Darwin options
/analyze --nixos "Search nix-darwin system options"
/analyze --nixos "Find macOS-specific configurations"
/analyze --nixos "Search for homebrew integration options"

# Darwin categories
/analyze --nixos "List all nix-darwin categories"
/analyze --nixos "Show nix-darwin statistics"
/analyze --nixos "Browse system.* options for macOS"

# Configuration details
/analyze --nixos "Get info about system.defaults options"
/analyze --nixos "Show launchd service configuration"
/analyze --nixos "Explain nix-darwin networking options"
```

**Flakes & Community Packages**
```bash
# Search flakes
/analyze --nixos "Search for neovim flakes"
/analyze --nixos "Find home-manager flakes"
/analyze --nixos "Search for development environment flakes"

# Flake statistics
/analyze --nixos "Show flake ecosystem statistics"
/analyze --nixos "Get community flake counts"
/analyze --nixos "Display popular flakes"

# Flake analysis
/analyze --nixos "Find flakes for rust development"
/analyze --nixos "Search for deployment tool flakes"
/analyze --nixos "Explore nixos configuration flakes"
```

**Development Workflows**
```bash
# Development environments
/build --nixos "Create Python development shell.nix"
/build --nixos "Generate Node.js project flake"
/design --nixos "Plan Rust development environment"

# Package management
/analyze --nixos "Find all available GCC versions"
/analyze --nixos "Search for development libraries"
/analyze --nixos "Check for specific tool availability"

# Configuration generation
/build --nixos "Generate basic NixOS configuration"
/build --nixos "Create Home Manager config for developer"
/build --nixos "Design modular NixOS setup"
```

**System Configuration**
```bash
# Service configuration
/analyze --nixos "Search for web server options"
/analyze --nixos "Find database service configurations"
/analyze --nixos "Explore container options"

# Security settings
/analyze --nixos "Search for firewall configuration"
/analyze --nixos "Find SELinux options"
/analyze --nixos "Explore hardening options"

# Hardware configuration
/analyze --nixos "Search for GPU driver options"
/analyze --nixos "Find audio configuration settings"
/analyze --nixos "Explore power management options"
```

**Integration Patterns**
```bash
# With development
/build --nixos "Create reproducible build environment"
/analyze --nixos "Find CI/CD tools in nixpkgs"
/design --nixos "Plan containerized Nix builds"

# With documentation
/document --nixos "Generate package list documentation"
/analyze --nixos "Document system configuration"
/build --nixos "Create deployment guide"

# With other tools
/analyze --nixos --openapi "Find API development packages"
/build --nixos --docker "Create Nix-based Docker images"
/design --nixos "Plan infrastructure as code"
```

**Troubleshooting & Debugging**
```bash
# Package issues
/troubleshoot --nixos "Why is package X not found"
/analyze --nixos "Check package availability across channels"
/troubleshoot --nixos "Debug dependency conflicts"

# Configuration problems
/troubleshoot --nixos "Fix option type mismatch"
/analyze --nixos "Validate configuration options"
/troubleshoot --nixos "Resolve module conflicts"

# Version issues
/analyze --nixos "Find compatible package versions"
/troubleshoot --nixos "Downgrade to specific version"
/analyze --nixos "Track breaking changes"
```

**Best Practices**
```bash
# Configuration management
/design --nixos "Structure modular NixOS config"
/improve --nixos "Optimize system configuration"
/document --nixos "Create configuration documentation"

# Package pinning
/analyze --nixos "Find stable package versions"
/build --nixos "Create pinned package set"
/design --nixos "Plan version management strategy"

# Reproducibility
/build --nixos "Ensure reproducible builds"
/analyze --nixos "Verify package hashes"
/design --nixos "Create hermetic environments"
```

**Common Patterns**
```bash
# Development shells
/build --nixos "Create multi-language dev shell"
/analyze --nixos "Find shell hook packages"
/design --nixos "Plan project environments"

# System profiles
/build --nixos "Create desktop configuration"
/build --nixos "Design server profile"
/analyze --nixos "Explore minimal configurations"

# Package overlays
/build --nixos "Create custom package overlay"
/analyze --nixos "Find overlay examples"
/design --nixos "Plan package customization"
```

**Tips for Success**
- Use specific channel names for consistent results
- Check package availability before configuration
- Leverage version history for compatibility
- Use Home Manager for user configurations
- Test configurations in VMs first
- Keep flake inputs updated
- Document custom configurations
- Use option search before implementation
- Pin package versions for stability
- Leverage community flakes
- Understand option types and defaults
- Regular channel updates for security
- Modularize complex configurations

### Pandoc (Universal Document Conversion)

**Overview**
Pandoc MCP server provides universal document format conversion between markdown, HTML, PDF, DOCX, LaTeX, EPUB, and more. Transform documents seamlessly with support for templates, filters, and custom styling options.

**Core Concepts**
- **Input/Output Formats**: Supported document types for conversion
- **Basic Formats**: MD, HTML, TXT, IPYNB, ODT (no special requirements)
- **Advanced Formats**: PDF, DOCX, RST, LaTeX, EPUB (require output file)
- **Reference Documents**: Style templates for DOCX output
- **Defaults Files**: YAML configuration for reusable conversion settings
- **Filters**: Custom processing scripts for enhanced conversions

**Installation**
```bash
# Install Pandoc MCP server
claude mcp add pandoc -- uvx mcp-pandoc

# For PDF support, install TeX Live:
# macOS: brew install texlive
# Linux: sudo apt-get install texlive-full
```

**Basic Conversions**
```bash
# Markdown to HTML
/task --pandoc "Convert README.md to HTML"
/task --pandoc "Transform docs/guide.md to HTML and display"
/task --pandoc "Convert markdown content '# Hello World' to HTML"

# HTML to Markdown
/task --pandoc "Convert webpage.html to markdown"
/task --pandoc "Transform index.html to clean markdown"
/task --pandoc "Extract markdown from HTML file"

# Text conversions
/task --pandoc "Convert notes.txt to markdown"
/task --pandoc "Transform README.md to plain text"
/task --pandoc "Convert formatted text to clean txt"
```

**Advanced Format Conversions**
```bash
# PDF generation (requires output file)
/task --pandoc "Convert report.md to PDF and save as report.pdf"
/task --pandoc "Transform thesis.md to academic.pdf with table of contents"
/task --pandoc "Generate slides.pdf from presentation.md"

# DOCX conversions
/task --pandoc "Convert manual.md to Word document manual.docx"
/task --pandoc "Transform report.html to report.docx"
/task --pandoc "Create proposal.docx from proposal.md"

# LaTeX conversions
/task --pandoc "Convert paper.md to LaTeX and save as paper.tex"
/task --pandoc "Transform equations.md to equations.tex"
/task --pandoc "Generate article.tex from research.md"

# EPUB creation
/task --pandoc "Convert book.md to EPUB and save as book.epub"
/task --pandoc "Transform novel.docx to novel.epub"
/task --pandoc "Create ebook.epub from chapters/*.md"
```

**Styled Document Creation**
```bash
# Using reference documents
/task --pandoc "Convert report.md to DOCX using corporate-template.docx as reference"
/task --pandoc "Transform proposal.md to styled Word doc with company-style.docx"
/task --pandoc "Create branded.docx from content.md using brand-template.docx"

# Custom styling
/task --pandoc "Convert CV.md to styled resume.docx with custom formatting"
/task --pandoc "Transform newsletter.md to formatted newsletter.docx"
/task --pandoc "Generate contract.docx with legal formatting"
```

**Using Defaults Files**
```bash
# Academic paper configuration
/build --pandoc "Create academic-paper.yaml defaults file with TOC, numbered sections, citations"
/task --pandoc "Convert thesis.md to PDF using defaults academic-paper.yaml"
/task --pandoc "Transform research.md with academic formatting defaults"

# Book configuration
/build --pandoc "Generate book-defaults.yaml for multi-chapter EPUB conversion"
/task --pandoc "Convert manuscript.md to EPUB using book-defaults.yaml"
/task --pandoc "Create formatted book with chapter navigation"

# Presentation defaults
/build --pandoc "Create slides-defaults.yaml for presentation formatting"
/task --pandoc "Convert talk.md to slides using presentation defaults"
```

**Batch Conversions**
```bash
# Multiple files
/task --pandoc "Convert all markdown files in docs/ to HTML"
/build --pandoc "Create script to batch convert *.md to PDF"
/task --pandoc "Transform all documentation to Word format"

# Directory processing
/analyze --pandoc "List all convertible files in project"
/task --pandoc "Convert entire documentation set to EPUB"
/build --pandoc "Create conversion pipeline for docs"
```

**Technical Documentation**
```bash
# API documentation
/document --pandoc "Convert OpenAPI spec to readable PDF documentation"
/task --pandoc "Transform API.md to formatted HTML with syntax highlighting"
/build --pandoc "Generate API reference from markdown sources"

# Code documentation
/task --pandoc "Convert README.md with code blocks to styled PDF"
/document --pandoc "Transform technical docs preserving code formatting"
/task --pandoc "Create developer guide with syntax highlighting"

# System documentation
/document --pandoc "Convert architecture.md to visual HTML documentation"
/task --pandoc "Transform deployment guide to PDF with diagrams"
/build --pandoc "Generate operations manual from markdown"
```

**Academic & Research**
```bash
# Papers and articles
/task --pandoc "Convert paper.md to LaTeX with citations"
/task --pandoc "Transform research.md to journal-ready PDF"
/build --pandoc "Create thesis template with proper formatting"

# Citations and bibliography
/task --pandoc "Convert paper with BibTeX citations to formatted PDF"
/document --pandoc "Generate reference list from markdown"
/build --pandoc "Create citation style configuration"

# Presentations
/task --pandoc "Convert slides.md to Beamer presentation"
/task --pandoc "Transform talk.md to reveal.js HTML slides"
/build --pandoc "Generate conference presentation template"
```

**Integration Workflows**
```bash
# With documentation systems
/document --pandoc --confluence "Convert and upload docs to Confluence"
/task --pandoc --git "Convert README and commit changes"
/build --pandoc "Create CI pipeline for doc generation"

# With content management
/task --pandoc --jira "Convert issue descriptions to formatted docs"
/document --pandoc "Transform project wiki to PDF handbook"
/build --pandoc "Create automated documentation workflow"

# With other tools
/analyze --pandoc --openapi "Convert API spec to readable docs"
/task --pandoc --excel "Transform spreadsheet data to markdown tables"
/document --pandoc --mermaid "Convert diagrams to embedded images"
```

**Custom Filters & Processing**
```bash
# Apply filters
/task --pandoc "Convert doc.md to HTML with custom-filter.py"
/task --pandoc "Transform with filters ['/filters/mermaid.py', '/filters/highlight.py']"
/build --pandoc "Create filter for diagram rendering"

# Processing pipelines
/build --pandoc "Create conversion pipeline with preprocessing"
/task --pandoc "Apply multiple filters in sequence"
/design --pandoc "Plan document processing workflow"
```

**Format-Specific Features**
```bash
# Jupyter notebooks
/task --pandoc "Convert analysis.ipynb to markdown"
/task --pandoc "Transform notebook.ipynb to PDF report"
/document --pandoc "Extract documentation from Jupyter notebook"

# reStructuredText
/task --pandoc "Convert Python docs from RST to markdown"
/task --pandoc "Transform sphinx docs to HTML"
/build --pandoc "Create RST to PDF pipeline"

# ODT (OpenDocument)
/task --pandoc "Convert ODT files to markdown"
/task --pandoc "Transform LibreOffice docs to Word"
/document --pandoc "Extract content from ODT files"
```

**Best Practices**
```bash
# Template management
/build --pandoc "Create document template library"
/design --pandoc "Plan conversion standards"
/document --pandoc "Create style guide for conversions"

# Quality control
/analyze --pandoc "Validate conversion output"
/improve --pandoc "Optimize conversion settings"
/test --pandoc "Check format compatibility"

# Automation
/build --pandoc "Create conversion automation scripts"
/design --pandoc "Plan batch processing workflow"
/task --pandoc "Set up watch folder for auto-conversion"
```

**Common Patterns**
```bash
# Documentation builds
/build --pandoc "Create docs build system"
/task --pandoc "Generate multi-format documentation"
/design --pandoc "Plan documentation pipeline"

# Publishing workflows
/build --pandoc "Create blog publishing pipeline"
/task --pandoc "Convert and format for publishing"
/document --pandoc "Generate print-ready documents"

# Archive conversions
/task --pandoc "Convert legacy documents to modern formats"
/build --pandoc "Create format migration tools"
/analyze --pandoc "Plan document modernization"
```

**Tips for Success**
- Always specify output files for advanced formats
- Use reference documents for consistent styling
- Create defaults files for repeated conversions
- Test filters before batch processing
- Preserve original files during conversion
- Use appropriate formats for target audience
- Consider file size for PDF generation
- Validate output format compatibility
- Document conversion workflows
- Automate repetitive conversions
- Keep pandoc and dependencies updated
- Use version control for templates

### Elasticsearch (Full-Text Search & Analytics)

**Overview**
Elasticsearch MCP server provides access to Elasticsearch and OpenSearch clusters for full-text search, analytics, and data management. Manage indices, documents, aliases, and perform complex queries through natural language commands.

**Core Concepts**
- **Indices**: Collections of documents (like database tables)
- **Documents**: Individual data records in JSON format
- **Mappings**: Schema definitions for documents
- **Aliases**: Alternative names for indices
- **Queries**: Search expressions using Query DSL
- **Clusters**: Groups of Elasticsearch nodes
- **Shards**: Index partitions for scalability

**Installation**
```bash
# Install Elasticsearch MCP server with credentials
claude mcp add elasticsearch -- ELASTICSEARCH_HOSTS="https://your-cluster.com:9200" ELASTICSEARCH_USERNAME="elastic" ELASTICSEARCH_PASSWORD="your-password" uvx elasticsearch-mcp-server

# For local Elasticsearch
claude mcp add elasticsearch -- ELASTICSEARCH_HOSTS="http://localhost:9200" uvx elasticsearch-mcp-server
```

**Index Management**
```bash
# List indices
/analyze --elasticsearch "List all indices in the cluster"
/analyze --elasticsearch "Show indices with their size and document count"
/analyze --elasticsearch "Find indices created in the last week"

# Index information
/analyze --elasticsearch "Get mappings and settings for products index"
/analyze --elasticsearch "Show field mappings for users index"
/analyze --elasticsearch "Check index health and shard allocation"

# Create indices
/build --elasticsearch "Create new index called logs with timestamp mapping"
/build --elasticsearch "Create products index with custom analyzer"
/build --elasticsearch "Set up index with 3 shards and 2 replicas"

# Delete indices
/cleanup --elasticsearch "Delete old log indices older than 30 days"
/task --elasticsearch "Remove test indices"
/cleanup --elasticsearch "Delete index named temp_data"
```

**Document Operations**
```bash
# Search documents
/analyze --elasticsearch "Search for products with price > 100"
/analyze --elasticsearch "Find documents containing 'error' in logs index"
/analyze --elasticsearch "Full-text search for 'machine learning' across all indices"

# Complex queries
/analyze --elasticsearch "Search users where age > 25 AND city = 'New York'"
/analyze --elasticsearch "Find products with fuzzy matching on name field"
/analyze --elasticsearch "Aggregation query for average price by category"

# Index documents
/task --elasticsearch "Index new product document with name, price, category"
/task --elasticsearch "Bulk index 100 user documents"
/build --elasticsearch "Create document pipeline for real-time ingestion"

# Get documents
/analyze --elasticsearch "Get document with ID 12345 from products index"
/analyze --elasticsearch "Retrieve user document by email address"
/analyze --elasticsearch "Fetch multiple documents by IDs"

# Update/Delete documents
/task --elasticsearch "Update product price for document ID 789"
/task --elasticsearch "Delete document with ID abc123"
/task --elasticsearch "Delete all documents where status = 'archived'"
```

**Search Queries**
```bash
# Basic searches
/analyze --elasticsearch "Simple match query for 'laptop' in products"
/analyze --elasticsearch "Wildcard search for 'log-*' indices"
/analyze --elasticsearch "Term query for exact matches"

# Advanced searches
/analyze --elasticsearch "Bool query with must, should, and must_not clauses"
/analyze --elasticsearch "Range query for dates between 2024-01-01 and 2024-12-31"
/analyze --elasticsearch "Geo-distance query for locations within 10km"

# Aggregations
/analyze --elasticsearch "Terms aggregation on category field"
/analyze --elasticsearch "Date histogram for daily counts"
/analyze --elasticsearch "Statistical aggregation for numeric fields"

# Full-text features
/analyze --elasticsearch "Phrase search with slop for flexible matching"
/analyze --elasticsearch "Highlighting search results"
/analyze --elasticsearch "Suggest queries for autocomplete"
```

**Cluster Operations**
```bash
# Cluster health
/analyze --elasticsearch "Check cluster health status"
/analyze --elasticsearch "Show cluster node information"
/analyze --elasticsearch "Display shard allocation across nodes"

# Cluster statistics
/analyze --elasticsearch "Get cluster-wide statistics"
/analyze --elasticsearch "Show index statistics summary"
/analyze --elasticsearch "Monitor cluster performance metrics"

# Cluster management
/task --elasticsearch "Perform cluster health check"
/analyze --elasticsearch "Identify unassigned shards"
/troubleshoot --elasticsearch "Diagnose cluster yellow status"
```

**Alias Management**
```bash
# List aliases
/analyze --elasticsearch "List all index aliases"
/analyze --elasticsearch "Show aliases for products index"
/analyze --elasticsearch "Find indices behind specific alias"

# Create aliases
/task --elasticsearch "Create alias 'current-logs' pointing to logs-2024"
/task --elasticsearch "Set up read alias for multiple indices"
/build --elasticsearch "Create filtered alias for active users"

# Update aliases
/task --elasticsearch "Switch alias from old index to new index"
/task --elasticsearch "Add index to existing alias"
/migrate --elasticsearch "Atomic alias swap for zero-downtime"

# Delete aliases
/cleanup --elasticsearch "Remove unused aliases"
/task --elasticsearch "Delete alias named 'temp-alias'"
```

**Data Analytics**
```bash
# Time-series analysis
/analyze --elasticsearch "Analyze log patterns over time"
/analyze --elasticsearch "Calculate hourly event rates"
/analyze --elasticsearch "Detect anomalies in time-series data"

# Business analytics
/analyze --elasticsearch "Sales aggregation by region and product"
/analyze --elasticsearch "Customer behavior analysis"
/analyze --elasticsearch "Revenue trends with moving averages"

# Performance metrics
/analyze --elasticsearch "API response time percentiles"
/analyze --elasticsearch "Error rate analysis by endpoint"
/analyze --elasticsearch "User engagement metrics"
```

**Advanced Workflows**
```bash
# Index lifecycle management
/design --elasticsearch "Create ILM policy for log rotation"
/build --elasticsearch "Set up hot-warm-cold architecture"
/task --elasticsearch "Configure automatic index rollover"

# Data pipelines
/build --elasticsearch "Create ingest pipeline with processors"
/design --elasticsearch "Set up data enrichment pipeline"
/task --elasticsearch "Configure grok patterns for log parsing"

# Security
/improve --elasticsearch --security "Set up index-level security"
/task --elasticsearch "Configure field-level security"
/build --elasticsearch "Create API key for application access"
```

**Integration Patterns**
```bash
# With databases
/migrate --elasticsearch --mongodb-localhost "Sync MongoDB data to Elasticsearch"
/build --elasticsearch "Create real-time sync from database"
/analyze --elasticsearch "Compare data between systems"

# With monitoring
/analyze --elasticsearch --time "Time-based log analysis"
/build --elasticsearch "Create monitoring dashboard data"
/task --elasticsearch "Set up alerting rules"

# With applications
/build --elasticsearch "Create search API wrapper"
/design --elasticsearch "Plan search architecture"
/document --elasticsearch "Generate search API documentation"
```

**Performance Optimization**
```bash
# Query optimization
/improve --elasticsearch "Optimize slow queries"
/analyze --elasticsearch "Profile query performance"
/design --elasticsearch "Plan query caching strategy"

# Index optimization
/improve --elasticsearch "Optimize index mappings"
/task --elasticsearch "Force merge for better performance"
/analyze --elasticsearch "Identify mapping conflicts"

# Resource management
/analyze --elasticsearch "Monitor heap usage"
/improve --elasticsearch "Tune shard allocation"
/troubleshoot --elasticsearch "Resolve memory pressure"
```

**Troubleshooting**
```bash
# Common issues
/troubleshoot --elasticsearch "Debug search returning no results"
/troubleshoot --elasticsearch "Fix mapping conflicts"
/analyze --elasticsearch "Investigate slow indexing"

# Cluster issues
/troubleshoot --elasticsearch "Resolve split-brain scenario"
/analyze --elasticsearch "Check for hot threads"
/troubleshoot --elasticsearch "Fix unassigned shards"

# Performance issues
/analyze --elasticsearch "Identify slow queries"
/troubleshoot --elasticsearch "Debug high CPU usage"
/improve --elasticsearch "Optimize garbage collection"
```

**Best Practices**
```bash
# Index design
/design --elasticsearch "Plan index structure for scalability"
/improve --elasticsearch "Optimize mapping for search performance"
/document --elasticsearch "Create index naming conventions"

# Query patterns
/build --elasticsearch "Create reusable query templates"
/improve --elasticsearch "Implement query best practices"
/analyze --elasticsearch "Review query efficiency"

# Operations
/document --elasticsearch "Create runbook for common tasks"
/build --elasticsearch "Set up monitoring and alerting"
/design --elasticsearch "Plan disaster recovery strategy"
```

**Common Patterns**
```bash
# Log analysis
/analyze --elasticsearch "Parse and analyze application logs"
/build --elasticsearch "Create log aggregation pipeline"
/task --elasticsearch "Set up log retention policy"

# Search implementation
/build --elasticsearch "Implement faceted search"
/design --elasticsearch "Create autocomplete functionality"
/improve --elasticsearch "Add search relevance tuning"

# Data management
/migrate --elasticsearch "Reindex with new mappings"
/task --elasticsearch "Implement data archival strategy"
/build --elasticsearch "Create backup and restore procedures"
```

**Tips for Success**
- Design mappings before indexing data
- Use aliases for zero-downtime updates
- Monitor cluster health regularly
- Implement proper index lifecycle management
- Use bulk operations for better performance
- Cache frequently used queries
- Keep indices reasonably sized
- Use appropriate number of shards
- Enable slow query logging
- Regular index maintenance
- Document your query patterns
- Test queries in development first
- Monitor resource usage closely

### Magic (AI-Powered UI Generation)

**Overview**
Magic is an AI-driven tool that creates beautiful, modern UI components through natural language descriptions. It provides access to a vast library of pre-built components inspired by 21st.dev.

**Installation**
```bash
# Install Magic MCP server with API key
claude mcp add magic npx @21st-dev/cli@latest install claude -- --api-key "your-api-key"

# Get API key from: https://21st.dev/magic
```

**Basic Component Generation**
```bash
# Simple component creation
/build --magic "Create a modern card component with image, title, and description"

# Navigation component
/build --magic --react "Build a responsive navigation bar with hamburger menu for mobile"

# Form components
/build --magic --react "Create a login form with email/password fields and social login buttons"

# Dashboard elements
/build --magic "Design a stats card showing revenue with trend indicator"
```

**Advanced UI Patterns**
```bash
# Hero sections
/build --magic --react --responsive "Create a hero section with gradient background, headline, CTA buttons, and animated elements"

# Data visualization
/build --magic "Build a dashboard widget showing real-time metrics with charts"

# E-commerce components
/build --magic --react "Design a product card with image carousel, pricing, and add to cart button"

# Social media patterns
/build --magic "Create a social media post component with reactions, comments, and share options"
```

**Design System Development**
```bash
# Component library setup
/design --magic --components --persona-frontend "Create a design system with buttons, inputs, cards, and modals"

# Theme-aware components
/build --magic --react "Build a button component that supports primary, secondary, and danger variants with dark mode"

# Accessibility-first design
/build --magic --accessibility "Create an accessible dropdown menu with keyboard navigation and ARIA labels"

# Animation and interactions
/build --magic "Design a notification toast component with slide-in animation and auto-dismiss"
```

**Complex UI Workflows**
```bash
# Multi-step forms
/build --magic --react --interactive "Create a multi-step onboarding form with progress indicator and validation"

# Data tables
/build --magic "Build a data table with sorting, filtering, pagination, and row selection"

# Modal systems
/build --magic --react "Design a modal system with nested modals, animations, and backdrop blur"

# Layout components
/build --magic --responsive "Create a responsive grid layout system with breakpoints"
```

**Integration Examples**
```bash
# With existing codebase
/build --magic --react --analyze "Create components matching our existing design patterns in src/components"

# TypeScript components
/build --magic --typescript "Build a typed form input component with validation"

# Tailwind CSS integration
/build --magic "Create a card component using Tailwind CSS classes"

# Component enhancement
/improve --magic "Enhance the existing Button component with loading states and icons"
```

**Mobile-First Development**
```bash
# Mobile navigation
/build --magic --responsive "Create a bottom navigation bar for mobile apps"

# Touch interactions
/build --magic --react "Build a swipeable card stack component for mobile"

# Responsive layouts
/build --magic "Design a responsive product grid that adapts from mobile to desktop"
```

**Performance Optimizations**
```bash
# Lazy-loaded components
/build --magic --performance "Create a lazy-loaded image gallery with intersection observer"

# Virtual scrolling
/build --magic --react "Build a virtual scroll list for handling thousands of items"

# Optimized animations
/build --magic "Design smooth animations using CSS transforms and will-change"
```

**Workflow Combinations**
```bash
# Full feature development
/design --magic --ddd --persona-architect "Design user profile system architecture"
/build --magic --react --tdd "Implement user profile card with tests"
/test --magic --e2e --playwright "Test user profile interactions"

# Rapid prototyping
/build --magic --react --watch "Create and iterate on dashboard components in real-time"

# Design to code
/design --magic --visual "Create high-fidelity mockups for landing page"
/build --magic --react "Convert mockups to React components"
```

**Best Practices**
- **Be Specific**: Provide detailed descriptions for better results
  ```bash
  # Good: Specific requirements
  /build --magic "Create a pricing card with monthly/yearly toggle, feature list, and gradient border"
  
  # Less effective: Too vague
  /build --magic "Make a card"
  ```

- **Iterate and Refine**: Use Magic to enhance existing components
  ```bash
  /improve --magic "Add hover effects and transitions to the Card component"
  ```

- **Combine with Personas**: Leverage personas for specialized needs
  ```bash
  /build --magic --persona-frontend --accessibility "Create WCAG-compliant form components"
  ```

- **Use with Version Control**: Track generated components
  ```bash
  /build --magic --human-review "Create new navigation component"
  # Automatically creates task documentation and branch
  ```

**Common Use Cases**
```bash
# Landing pages
/build --magic --react "Create a SaaS landing page hero with features grid"

# Admin dashboards
/build --magic "Design an admin sidebar with collapsible menu items"

# User interfaces
/build --magic --react "Build a user settings page with tabs and form sections"

# Marketing components
/build --magic "Create a testimonial carousel with company logos"

# Interactive elements
/build --magic --react "Design an interactive pricing calculator"
```

**Tips for Success**
1. **Use Natural Language**: Describe components as you would to a designer
2. **Specify Frameworks**: Include React, Vue, or vanilla JS preferences
3. **Include Styling Preferences**: Mention Tailwind, CSS modules, or styled-components
4. **Add Functionality Details**: Describe interactions and behaviors
5. **Request Variations**: Ask for multiple versions to choose from

### Puppeteer (Browser Automation & Testing)

**Overview**
Puppeteer provides browser automation capabilities for web testing, scraping, and interaction. It offers both headed (visible browser) and headless modes for different use cases.

**Installation**
```bash
# Headed mode (visible browser)
claude mcp add puppeteer -- npx -y @modelcontextprotocol/server-puppeteer

# Headless mode (no visible browser, runs in Docker)
claude mcp add puppeteer-headless -- docker run -i --rm --init -e DOCKER_CONTAINER=true mcp/puppeteer
```

**Basic Browser Automation**
```bash
# Navigate to a webpage (headed mode)
/test --pup "Navigate to https://example.com"

# Navigate with headless mode
/test --pup-headless "Navigate to https://example.com"

# Take a screenshot
/test --pup "Navigate to https://github.com and take screenshot named 'github-home'"

# Capture specific element
/test --pup "Screenshot the login form at https://example.com/login" --selector "#login-form"
```

**Web Interaction**
```bash
# Click elements
/test --pup "Navigate to https://example.com and click the 'Sign Up' button"
/test --pup --click "button.signup-btn"

# Hover over elements
/test --pup "Hover over the dropdown menu" --hover "#nav-dropdown"

# Fill forms
/test --pup "Fill login form" --fill "#username" "testuser@example.com"
/test --pup --fill "#password" "securepassword" --click "#login-btn"

# Select dropdown options
/test --pup --select "#country-select" "United States"
```

**E2E Testing Workflows**
```bash
# Complete user flow testing
/test --pup --e2e "Test user registration flow"
# 1. Navigate to signup page
# 2. Fill registration form
# 3. Submit and verify success
# 4. Check welcome email

# Shopping cart test
/test --pup --e2e --persona-qa "Test add to cart functionality"
/test --pup --navigate "https://shop.example.com"
/test --pup --click ".product-card:first-child .add-to-cart"
/test --pup --screenshot "cart-with-item"

# Multi-step form testing
/test --pup --seq "Test multi-page checkout process"
```

**JavaScript Execution**
```bash
# Execute custom JavaScript
/test --pup --evaluate "document.title"
/test --pup --evaluate "window.localStorage.getItem('user-token')"

# Inject scripts
/test --pup --evaluate "
  const buttons = document.querySelectorAll('button');
  return buttons.length;
"

# Modify page content
/test --pup --evaluate "
  document.querySelector('h1').textContent = 'Modified Title';
"

# Extract data
/analyze --pup --evaluate "
  Array.from(document.querySelectorAll('.price')).map(el => el.textContent)
"
```

**Visual Testing**
```bash
# Full page screenshots
/test --pup --screenshot "full-page" --width 1920 --height 1080

# Mobile viewport testing
/test --pup --screenshot "mobile-view" --width 375 --height 667

# Element-specific screenshots
/test --pup --screenshot "header" --selector "header.main-header"

# Visual regression testing
/test --pup --visual --regression "Compare homepage layouts"
/test --pup --screenshot "homepage-v1" 
# After changes:
/test --pup --screenshot "homepage-v2"
/analyze "Compare homepage-v1 and homepage-v2 screenshots"
```

**Console Monitoring**
```bash
# Monitor console logs
/test --pup --console "Navigate to app and check for errors"
/analyze --pup "Read console://logs"

# Debug JavaScript errors
/troubleshoot --pup "Navigate to https://app.example.com and monitor console"
/analyze "Check console://logs for errors"

# Performance monitoring
/test --pup --evaluate "performance.timing" 
/analyze --performance "Analyze page load metrics"
```

**Headless vs Headed Mode**
```bash
# Headless mode (faster, no UI)
/test --pup-headless "Automated testing in CI/CD"
/test --pup-headless --screenshot "ci-test-result" --encoded
# Returns base64 encoded image for easy integration

# Headed mode (visual debugging)
/test --pup "Debug form submission issue"
# See actual browser interaction

# Custom launch options (headed mode only)
/test --pup --launch-options '{"headless": false, "slowMo": 500}'
# Slow down for debugging

# Security-restricted options
/test --pup --launch-options '{"args": ["--disable-web-security"]}' --allow-dangerous
# Requires explicit permission
```

**Advanced Automation**
```bash
# Page navigation with wait conditions
/test --pup "Navigate and wait for content to load"
/test --pup --evaluate "document.readyState === 'complete'"

# Network request interception
/test --pup --seq "Monitor API calls during page load"

# Cookie management
/test --pup --evaluate "document.cookie"
/test --pup --evaluate "document.cookie = 'session=abc123; path=/'"

# Local storage manipulation
/test --pup --evaluate "localStorage.setItem('theme', 'dark')"
/test --pup --evaluate "localStorage.getItem('theme')"
```

**Testing Scenarios**
```bash
# Authentication testing
/test --pup --tdd "Test login functionality"
# Red: Write failing test for login
# Green: Implement login interaction
# Refactor: Optimize selectors

# Responsive design testing
/test --pup --responsive "Test mobile breakpoints"
/test --pup --screenshot "desktop" --width 1920 --height 1080
/test --pup --screenshot "tablet" --width 768 --height 1024
/test --pup --screenshot "mobile" --width 375 --height 667

# Performance testing
/analyze --pup --performance "Measure page load times"
/test --pup --evaluate "performance.getEntriesByType('navigation')[0]"

# Accessibility testing
/test --pup --accessibility "Check ARIA labels"
/test --pup --evaluate "document.querySelectorAll('[aria-label]').length"
```

**Integration Examples**
```bash
# Puppeteer + Sequential for complex flows
/test --pup --seq "Test complete user journey from signup to purchase"

# Puppeteer + Memory for test data
/test --pup --memory "Store test credentials for reuse"
/task --memory create-entities '[{"name": "Test_User", "entityType": "test-data", "observations": ["email: test@example.com", "password: TestPass123"]}]'

# Puppeteer + Time for scheduling
/test --pup --time "Run visual regression tests at 2 AM EST daily"

# Puppeteer + Fetch for comparison
/analyze --pup --fetch "Compare rendered vs source HTML"
```

**CI/CD Integration**
```bash
# Headless for CI pipelines
/test --pup-headless --e2e "Run full test suite"
/test --pup-headless --screenshot "test-results" --encoded
# Process base64 results in CI

# Parallel testing
/test --pup-headless --parallel "Run tests across multiple browsers"

# Test reporting
/test --pup-headless --report "Generate test results in JSON"
/test --pup-headless --evaluate "window.__testResults__"
```

**Best Practices**

1. **Use Appropriate Mode**
   ```bash
   # Headless for: CI/CD, automated testing, performance
   /test --pup-headless --e2e
   
   # Headed for: debugging, visual verification, development
   /test --pup --debug
   ```

2. **Reliable Selectors**
   ```bash
   # Good: Data attributes
   /test --pup --click "[data-testid='submit-button']"
   
   # Avoid: Fragile selectors
   /test --pup --click "div > span.btn-primary:nth-child(3)"
   ```

3. **Wait Strategies**
   ```bash
   # Wait for elements
   /test --pup --evaluate "document.querySelector('#content') !== null"
   
   # Wait for network
   /test --pup --evaluate "window.fetch_complete === true"
   ```

4. **Error Handling**
   ```bash
   # Check console for errors
   /test --pup --console "Run tests and check for errors"
   /analyze "console://logs" --filter "error"
   ```

**Common Use Cases**
```bash
# Form validation testing
/test --pup "Test form validation messages"

# PDF generation
/test --pup --screenshot "invoice" --format "pdf"

# Social media preview testing
/test --pup "Check Open Graph meta tags"

# Cookie consent testing
/test --pup "Test GDPR cookie banner interactions"

# Search functionality
/test --pup "Test search autocomplete feature"
```

**Tips for Success**
- Use headless mode for faster execution in CI/CD
- Use headed mode for debugging and development
- Always use reliable selectors (data-testid preferred)
- Monitor console logs for JavaScript errors
- Take screenshots at key points for debugging
- Use --encoded for base64 screenshots in automation
- Combine with other MCP servers for comprehensive testing
- Set appropriate viewport sizes for responsive testing

### Playwright (Advanced Browser Automation)

**Installation**
```bash
# Install Playwright MCP server
claude mcp add playwright npx @playwright/mcp@latest
```

**Basic Usage**
```bash
# Enable Playwright for E2E testing
/test --e2e --playwright --persona-qa --coverage

# Record browser sessions
/test --e2e --playwright --record --persona-qa

# Cross-browser testing
/test --e2e --playwright --browsers chrome,firefox,webkit --persona-qa

# Mobile device testing
/test --e2e --playwright --device "iPhone 15" --persona-qa
```

**Advanced Configuration Options**
```bash
# Headless mode (default is headed)
/test --e2e --playwright --headless --persona-qa

# Custom viewport size
/test --e2e --playwright --viewport "1920,1080" --persona-qa

# Ignore HTTPS errors
/test --e2e --playwright --ignore-https-errors --persona-qa

# Custom user agent
/test --e2e --playwright --user-agent "Custom UA String" --persona-qa

# Proxy configuration
/test --e2e --playwright --proxy "http://myproxy:3128" --persona-qa

# Block service workers
/test --e2e --playwright --block-service-workers --persona-qa
```

**Browser-Specific Testing**
```bash
# Chrome/Edge testing
/test --e2e --playwright --browser chrome --persona-qa

# Firefox testing
/test --e2e --playwright --browser firefox --persona-qa

# WebKit/Safari testing
/test --e2e --playwright --browser webkit --persona-qa

# Multi-browser testing
/test --e2e --playwright --all-browsers --persona-qa
```

**Performance & Visual Testing**
```bash
# Performance profiling with traces
/test --performance --playwright --save-trace --persona-performance

# Visual regression testing
/test --visual --playwright --screenshots --persona-qa

# Accessibility testing
/test --accessibility --playwright --persona-qa --strict

# Network monitoring
/analyze --network --playwright --monitor --persona-performance
```

**Session Management**
```bash
# Save browser state
/test --e2e --playwright --save-state "auth.json" --persona-qa

# Reuse authentication state
/test --e2e --playwright --storage-state "auth.json" --persona-qa

# Isolated session (in-memory profile)
/test --e2e --playwright --isolated --persona-qa

# Custom user data directory
/test --e2e --playwright --user-data-dir "/path/to/profile" --persona-qa
```

**Output & Debugging**
```bash
# Save test artifacts
/test --e2e --playwright --output-dir "./test-results" --persona-qa

# Enable trace recording
/test --e2e --playwright --save-trace --output-dir "./traces" --persona-qa

# Debug mode with slowmo
/test --e2e --playwright --debug --slowmo 500 --persona-qa

# Verbose logging
/test --e2e --playwright --verbose --persona-qa
```

**Content Security**
```bash
# Allow specific origins
/test --e2e --playwright --allowed-origins "https://example.com;https://api.example.com" --persona-security

# Block specific origins
/test --e2e --playwright --blocked-origins "https://ads.example.com;https://tracking.example.com" --persona-security

# Combined origin control
/test --e2e --playwright --allowed-origins "https://*.myapp.com" --blocked-origins "https://ads.*" --persona-security
```

**Playwright vs Puppeteer**
- **Playwright**: Cross-browser support (Chrome, Firefox, WebKit), better mobile emulation, built-in trace viewer
- **Puppeteer**: Chrome/Chromium focused, lighter weight, simpler API
- Use `--playwright` for cross-browser testing and advanced features
- Use `--pup` for Chrome-specific automation and simpler use cases

### MongoDB (Database Operations)

**Installation**
```bash
# Install MongoDB MCP server
claude mcp add mongodb-localhost npx mongodb-mcp-server -- --connectionString="mongodb://localhost:27017/"
```

**Basic Usage**
```bash
# Enable MongoDB for database operations
/analyze --mongodb-localhost --persona-backend

# Connect to MongoDB
/troubleshoot --mongodb-localhost --connect "mongodb://localhost:27017/myapp"

# Query operations
/analyze --mongodb-localhost --find "users" --filter '{"active": true}'

# Data migrations
/migrate --mongodb-localhost --persona-backend --plan
```

**Database Operations**
```bash
# List databases and collections
/analyze --mongodb-localhost --list-databases --persona-backend
/analyze --mongodb-localhost --list-collections "myapp" --persona-backend

# Query operations
/analyze --mongodb-localhost --find "users" --query '{"email": "user@example.com"}'
/analyze --mongodb-localhost --count "orders" --filter '{"status": "pending"}'

# Aggregation pipelines
/analyze --mongodb-localhost --aggregate "sales" --pipeline '[
  {"$match": {"date": {"$gte": "2024-01-01"}}},
  {"$group": {"_id": "$product", "total": {"$sum": "$amount"}}}
]'

# Schema analysis
/analyze --mongodb-localhost --collection-schema "products" --persona-analyzer
/analyze --mongodb-localhost --collection-indexes "users" --persona-performance
```

**Data Manipulation**
```bash
# Insert operations
/build --mongodb-localhost --insert-one "users" --document '{"name": "John", "email": "john@example.com"}'
/build --mongodb-localhost --insert-many "products" --documents '[
  {"name": "Product A", "price": 29.99},
  {"name": "Product B", "price": 49.99}
]'

# Update operations
/improve --mongodb-localhost --update-one "users" --filter '{"_id": "123"}' --update '{"$set": {"verified": true}}'
/improve --mongodb-localhost --update-many "orders" --filter '{"status": "shipped"}' --update '{"$set": {"completed": true}}'

# Delete operations
/cleanup --mongodb-localhost --delete-one "sessions" --filter '{"expired": true}'
/cleanup --mongodb-localhost --delete-many "logs" --filter '{"timestamp": {"$lt": "2023-01-01"}}'
```

**Database Management**
```bash
# Collection management
/build --mongodb-localhost --create-index "users" --index '{"email": 1}' --options '{"unique": true}'
/migrate --mongodb-localhost --rename-collection "old_users" "users_archive"
/cleanup --mongodb-localhost --drop-collection "temp_data" --confirm

# Database operations
/analyze --mongodb-localhost --db-stats "myapp" --persona-performance
/analyze --mongodb-localhost --collection-storage-size "uploads" --persona-performance
/cleanup --mongodb-localhost --drop-database "test_db" --force --confirm
```

**Performance & Optimization**
```bash
# Index optimization
/improve --mongodb-localhost --create-index "orders" --index '{"user_id": 1, "created_at": -1}'
/analyze --mongodb-localhost --collection-indexes "products" --persona-performance

# Query performance
/analyze --mongodb-localhost --find "users" --filter '{"age": {"$gte": 18}}' --index-check
/troubleshoot --mongodb-localhost --aggregate "sales" --explain --persona-performance

# Storage analysis
/analyze --mongodb-localhost --collection-storage-size "documents" --persona-performance
/analyze --mongodb-localhost --db-stats "production" --detailed
```

**Security Configuration**
```bash
# Read-only mode
/analyze --mongodb-localhost --read-only --find "sensitive_data"

# Disable specific operations
/analyze --mongodb-localhost --disabled-tools "drop-database,drop-collection"

# Index requirement enforcement
/analyze --mongodb-localhost --index-check --find "large_collection"
```

**Integration Examples**
```bash
# Data migration workflow
/migrate --mongodb-localhost --persona-backend --plan
# 1. Analyze source schema
# 2. Create target collections
# 3. Transform and insert data
# 4. Verify data integrity
# 5. Create indexes

# Performance optimization
/analyze --mongodb-localhost --collection-schema "orders" --persona-performance
/improve --mongodb-localhost --create-index "orders" --compound --persona-performance
/test --mongodb-localhost --query-performance --persona-performance

# Backup and restore
/task --mongodb-localhost --backup "production" --persona-backend
/migrate --mongodb-localhost --restore "production_backup" --persona-backend
```

**Best Practices**
- Always use `--index-check` for production queries
- Enable `--read-only` when analyzing sensitive data
- Use aggregation pipelines for complex queries
- Monitor collection sizes with storage analysis
- Create appropriate indexes before deploying
- Use `--plan` flag for migration operations

## 🔄 Human Review Workflow

### Overview
The `--human-review` flag (enabled by default) creates a structured workflow for continuous integration with human oversight. It documents every task, creates feature branches, and maintains comprehensive documentation for review.

### Basic Usage
```bash
# Start a new task with human review (default)
/build --feature "user authentication"

# Disable human review for quick changes
/build --fix --no-human-review "typo in readme"

# Complex task with full documentation
/design --api --ddd --human-review "payment system"
```

### Task Documentation Structure
Each task creates a `tasks/[id]-[summary].md` file:

```markdown
# Specification

## Objective
Clear statement of what needs to be accomplished

## Requirements
- Functional requirements
- Technical requirements

## Constraints
- Technical limitations
- Business rules

## Success Criteria
- Measurable outcomes
- Acceptance criteria

# Implementation

## Step 1: [Description]
- **Action**: What was done
- **Rationale**: Why this approach
- **Changes**: Files modified/created
- **Commit**: [hash] commit message

## Step 2: [Description]
...

# Summary

## Changes Made
- High-level summary of changes
- Impact on the system

## Technical Decisions
- **Decision**: Architecture choice
  **Rationale**: Reasoning behind it

## Testing
- Test coverage added
- Test results

## Next Steps
- Follow-up tasks
- Future improvements
```

### Git Workflow Integration
```bash
# Automatic branch creation
# Branch name: tasks/0001-add_user_authentication

# With TDD enabled
🧪 [0001] Add failing test for user validation
✅ [0001] Implement user validation
🚀 [0001] Refactor validation to use strategy pattern

# Without TDD
✨ [0001] Add user authentication feature
🐛 [0001] Fix validation edge case
📝 [0001] Document authentication API
```

### Documentation Updates

**Journal Updates** (per module):
```markdown
## [Date] - Task 0001: Add user authentication

### Changes
- Added AuthController
- Implemented JWT tokens
- Created user validation

### Impact
- New authentication flow
- Breaking change to API v1

### Technical Notes
- Uses RS256 for token signing
- 24-hour token expiry
```

**Story Creation** (when applicable):
```markdown
# User Authentication: A Story

## The Challenge
Users couldn't securely access their personal data...

## The Journey
We explored OAuth, session-based auth, and JWT...

## The Solution
A stateless JWT system with refresh tokens...

## The Impact
Users now have secure, seamless access...
```

### Workflow Examples

**Feature Development**
```bash
# Start feature with human review
/build --feature --human-review "shopping cart"
# Creates: tasks/0001-add_shopping_cart.md
# Branch: tasks/0001-add_shopping_cart
# Commits tracked with task ID

# Complete with documentation
# - Updates module journal.md files
# - Creates stories/0001-add_shopping_cart.md
# - Updates main story.md if significant
```

**Bug Fix Workflow**
```bash
# Investigate and fix with documentation
/troubleshoot --fix --human-review "memory leak"
# Creates: tasks/0002-fix_memory_leak.md
# Documents investigation process
# Tracks fix implementation
```

**Refactoring with Review**
```bash
# Refactor with full documentation
/improve --refactor --human-review --tdd "database layer"
# Creates: tasks/0003-refactor_database_layer.md
# TDD workflow with red/green/refactor
# Comprehensive change documentation
```

### CI/CD Integration

**Pull Request Template**
```markdown
## Task: 0001 - Add user authentication

### Documentation
- Task document: `tasks/0001-add_user_authentication.md`
- Story: `stories/0001-add_user_authentication.md`

### Changes
[Summary from task document]

### Testing
[Testing summary from task document]

### Review Checklist
- [ ] Task specification met
- [ ] Tests passing
- [ ] Documentation updated
- [ ] journal.md files updated
- [ ] Story created (if applicable)
```

### Best Practices

**When to Use Human Review**
- Feature development
- Bug fixes with investigation
- Refactoring efforts
- Architecture changes
- Any changes requiring documentation

**When to Disable**
- Emergency hotfixes
- Typo corrections
- Configuration updates
- Development experiments

**Task ID Management**
- IDs are sequential (0001, 0002, etc.)
- Never reuse IDs
- IDs persist across branches
- Include ID in all commits

**Documentation Quality**
- Clear, concise specifications
- Detailed implementation steps
- Rationale for decisions
- Comprehensive test coverage
- Actionable next steps

## 📊 Monitoring & Metrics

### Performance Tracking
```bash
# Continuous performance monitoring
/analyze --performance --watch --persona-performance --pup --monitor

# Performance baseline establishment
/test --performance --baseline --persona-performance --pup --metrics

# Performance regression detection
/analyze --performance --regression --persona-performance --profile --alert
```

### Quality Metrics
```bash
# Code quality monitoring
/analyze --quality --metrics --persona-refactorer --iterate --evidence

# Test coverage tracking
/test --coverage --metrics --persona-qa --comprehensive --tracking

# Security posture monitoring
/scan --security --metrics --persona-security --continuous --alerts
```

### Development Velocity
```bash
# Velocity tracking
/analyze --velocity --metrics --persona-architect --seq --tracking

# Bottleneck identification
/analyze --bottlenecks --development --persona-performance --profile

# Process optimization
/improve --process --velocity --persona-architect --iterate
```

## 🔧 Troubleshooting Guide

### Common Issues & Solutions

**MCP Server Not Responding**
```bash
# Check MCP server health
/troubleshoot --mcp --health --persona-analyzer --seq

# Fallback to native tools
/analyze --code --no-mcp --persona-refactorer

# Reset MCP connections
/troubleshoot --mcp --reset --persona-analyzer
```

**Performance Issues**
```bash
# Identify performance bottlenecks
/analyze --profile --bottlenecks --persona-performance --pup --seq

# Optimize token usage
/analyze --code --uc --no-mcp --persona-refactorer

# Monitor resource usage
/analyze --performance --resources --persona-performance --monitor
```

**Context Limit Exceeded**
```bash
# Enable ultra-compressed mode
/analyze --code --uc --persona-refactorer

# Use selective analysis
/analyze --code --files src/ --persona-refactorer --uc

# Progressive analysis
/analyze --code --incremental --persona-refactorer --uc
```

**Build Failures**
```bash
# Systematic debugging
/troubleshoot --build --systematic --persona-analyzer --seq

# Dependency analysis
/analyze --dependencies --persona-backend --c7

# Clean rebuild
/cleanup --build --persona-refactorer --validate
```

### Best Practices

**Efficient Workflow Design**
- Start with `--plan` for complex operations
- Use `--dry-run` for destructive operations
- Combine `--watch` with `--interactive` for guided development
- Apply `--uc` mode when approaching context limits

**Persona Selection**
- Choose personas based on primary task focus
- Switch personas for different workflow phases
- Use `--introspect` for learning persona behaviors
- Combine multiple personas for complex projects

**MCP Server Usage**
- Use `--c7` for external library integration
- Apply `--seq` for complex analysis tasks
- Enable `--magic` for UI development
- Utilize `--pup` for browser automation
- Fall back to `--no-mcp` when servers are slow

**Quality Assurance**
- Always use `--validate` for production deployments
- Apply `--strict` mode for critical operations
- Use `--evidence` for decision documentation
- Combine `--coverage` with `--comprehensive` for thorough testing

---

*SuperClaude v2.0.1 - Comprehensive usage guide for all commands, personas, and flags*