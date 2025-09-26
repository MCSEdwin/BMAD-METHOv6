# 🚀 BMAD Next.js Feature-Based Architecture Extension Pack

A comprehensive AI-powered Next.js 15+ development framework using Feature-Based Architecture and Domain-Driven Design principles, built on the `marciobarroso/nextjs-new-app` template.

## 📋 Overview

This extension pack provides everything needed to build enterprise-grade Next.js applications following Feature-Based Architecture patterns. Built specifically for the `nextjs-new-app` template, it includes specialized AI agents, Domain-Driven Design workflows, BaseController patterns, and schema-first development to accelerate your development process.

## ✨ Features

### 🤖 Specialized AI Agents

- **Domain Architect** - Business domain modeling and bounded context definition
- **Next.js Architect** - Feature-Based Architecture and App Router patterns
- **BaseController Specialist** - Database-agnostic controller patterns and schema-first design
- **TypeScript Specialist** - Strict type safety and advanced TypeScript patterns
- **Tailwind Designer** - Tailwind CSS 4.x design with utility-first approach
- **API Developer** - RESTful API design following BaseController patterns
- **Database Specialist** - Database-agnostic integration (Prisma, MongoDB, etc.)
- **Auth Specialist** - Authentication and authorization integration
- **Testing Engineer** - Feature-based testing strategies
- **Deployment Specialist** - Production deployment for Feature-Based Architecture
- **Performance Optimizer** - Next.js 15+ optimization and Core Web Vitals
- **Security Auditor** - Security best practices for modern web applications

### 🔄 Domain-Driven Workflows

- **Feature-Based Project Setup** - Initialize project from `nextjs-new-app` template
- **Domain Feature Development** - Complete business domain implementation
- **BaseController Implementation** - Database-agnostic controller setup
- **Cross-Feature Integration** - Manage dependencies between features
- **Schema-First Development** - Zod validation and type-safe patterns
- **Testing Pipeline** - Feature-based testing strategies
- **Deployment Pipeline** - Production deployment with Feature-Based Architecture

### 📝 Architecture Templates

- Feature Structure Template (Complete feature organization)
- BaseController Extension Template (Database-agnostic controller)
- Schema-First Entity Template (Zod validation + TypeScript types)
- Feature Component Template (React + TypeScript + Tailwind)
- API Route Template (BaseController integration)
- Custom Hooks Template (Data fetching patterns)

### ✅ Architecture Checklists

- Feature-Based Architecture Development Checklist
- BaseController Implementation Checklist
- Domain-Driven Design Checklist
- Schema-First Development Checklist
- Cross-Feature Integration Checklist

## 🚀 Quick Start

### Template Base

This extension pack is designed to work with the `nextjs-new-app` template:

```bash
# Clone the base template
git clone https://github.com/marciobarroso/nextjs-new-app.git my-project
cd my-project

# Install dependencies
pnpm install # or npm install
```

### Extension Pack Usage

```bash
# Use BMAD Method with this extension pack
bmad-fba create-feature "user-management"

# Implement domain feature
bmad-fba develop-domain "order-processing"

# Setup BaseController pattern
bmad-fba implement-controller "Product"
```

## 🏗️ Feature-Based Architecture

This extension pack implements Feature-Based Architecture with Domain-Driven Design:

- **Next.js 15+ App Router** - Modern routing with route groups
- **Feature-Based Organization** - `(features)/` directory structure
- **Domain-Driven Design** - Business domain bounded contexts
- **BaseController Pattern** - Database-agnostic CRUD operations
- **Schema-First Development** - Zod validation with TypeScript
- **Server/Client Components** - Optimized rendering patterns
- **Tailwind CSS 4.x** - Modern utility-first styling
- **Database Agnostic** - Support for any ORM/ODM (Prisma, TypeORM, Mongoose)
- **Shared Infrastructure** - Common utilities and patterns

## 📚 Documentation

### Core Concepts

- [Project Structure](docs/project-structure.md)
- [Component Patterns](docs/component-patterns.md)
- [API Design](docs/api-design.md)
- [State Management](docs/state-management.md)

### Guides

- [Getting Started](docs/getting-started.md)
- [Development Workflow](docs/development-workflow.md)
- [Testing Strategy](docs/testing-strategy.md)
- [Deployment Guide](docs/deployment-guide.md)

## 🛠️ Technology Stack

### Core Technologies (from nextjs-new-app template)

- **Next.js 15.5.3** - React framework with App Router
- **React 19.1.0** - Latest React with modern features
- **TypeScript 5** - Strict type safety
- **Tailwind CSS 4.1.13** - Modern utility-first CSS
- **PostCSS 8.5.6** - CSS processing
- **pnpm** - Efficient package management

### Development Tools (pre-configured)

- **ESLint 9** - Code linting with Next.js integration
- **Prettier 3.6.2** - Code formatting with import sorting
- **Husky 9.1.7** - Git hooks for code quality
- **Jest** - Testing framework (configured, ready for implementation)

### Feature-Based Architecture Additions

- **Zod** - Schema validation and type generation
- **BaseController Pattern** - Database-agnostic CRUD operations
- **Domain-Driven Design** - Business domain organization
- **Schema-First Development** - Type-safe data modeling

## 🎯 Best Practices

### Code Quality

- Strict TypeScript configuration
- Comprehensive ESLint rules
- Automatic code formatting with Prettier
- Component-driven development
- API-first design approach

### Performance

- Server Components by default
- Client Components only when needed
- Image optimization with Next.js Image
- Bundle analysis and optimization
- Core Web Vitals monitoring

### Security

- Input validation with Zod
- CSRF protection
- Secure headers middleware
- Environment variable management
- Authentication best practices

## 📦 Project Structure

```
app/
├── (features)/              # Feature modules (Domain-Driven Design)
│   ├── (user-management)/   # Business domain example
│   │   ├── api/            # Backend API layer
│   │   │   └── users/      # Entity-specific routes
│   │   │       ├── [id]/   # Dynamic routes
│   │   │       ├── controller.ts # BaseController extension
│   │   │       ├── route.ts    # Collection operations
│   │   │       └── schema.ts   # Zod schemas & types
│   │   ├── components/     # Feature-specific UI
│   │   ├── hooks/          # Custom React hooks
│   │   ├── types/          # TypeScript definitions
│   │   └── users/          # Feature pages
│   └── (order-processing)/ # Another business domain
├── shared/                 # Shared infrastructure
│   ├── components/ui/      # Reusable UI components
│   ├── core/              # BaseController & patterns
│   ├── lib/               # Utilities
│   └── types/             # Shared types
├── globals.css            # Global styles
├── layout.tsx             # Root layout
└── page.tsx               # Home page
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests for new functionality
5. Ensure all tests pass
6. Submit a pull request

## 📄 License

This extension pack is part of the BMAD Method project and follows the same MIT license.

## 🆘 Support

- [Documentation](docs/)
- [GitHub Issues](https://github.com/marciobarroso/BMAD-METHOD/issues)
- [Discussions](https://github.com/marciobarroso/BMAD-METHOD/discussions)

## 🏷️ Version

**Current Version:** 1.0.0

**Compatibility:**

- Next.js 15+
- Node.js 20.10.0+
- TypeScript 5+

---

Built with ❤️ using the BMAD Method framework.
