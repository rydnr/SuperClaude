# Authentication System

## Overview
Implement a secure, scalable authentication system with support for local accounts and OAuth2 providers (Google, GitHub). This milestone establishes the foundation for user management and access control throughout the application.

## Success Criteria
- [ ] Users can register with email/password
- [ ] Users can login and logout securely
- [ ] OAuth2 integration with Google and GitHub
- [ ] Password reset functionality via email
- [ ] Session management with JWT tokens
- [ ] Rate limiting on auth endpoints
- [ ] Account verification via email
- [ ] Remember me functionality
- [ ] Secure password storage (bcrypt)
- [ ] CSRF protection implemented

## Tasks

### 1. Database Schema Design
- **Command**: `/design --schema --ddd --bounded-context`
- **Persona**: architect
- **Thinking**: think-hard
- **MCPs**: c7, seq
- **Description**: Design user, session, and auth provider tables following DDD principles
- **Expected Outcome**: Schema migrations ready, bounded contexts defined

### 2. Security Planning
- **Command**: `/analyze --security --auth --owasp`
- **Persona**: security
- **Thinking**: ultrathink
- **MCPs**: c7, seq
- **Description**: Review auth flow against OWASP guidelines, identify security requirements
- **Expected Outcome**: Security checklist, threat model documented

### 3. API Endpoints Design
- **Command**: `/design --api --rest --openapi`
- **Persona**: backend
- **Thinking**: think
- **MCPs**: c7, openapi
- **Description**: Design RESTful auth endpoints with OpenAPI specification
- **Expected Outcome**: OpenAPI spec for auth endpoints

### 4. Auth Service Implementation
- **Command**: `/build --api --tdd --auth`
- **Persona**: backend
- **Thinking**: think
- **MCPs**: c7
- **Description**: Implement core authentication service with TDD
- **Expected Outcome**: Auth service with 90%+ test coverage

### 5. OAuth2 Integration
- **Command**: `/build --feature "oauth2 providers" --tdd`
- **Persona**: backend
- **Thinking**: think-hard
- **MCPs**: c7, seq
- **Description**: Integrate Google and GitHub OAuth2 providers
- **Expected Outcome**: Working OAuth2 flow with both providers

### 6. Frontend Components
- **Command**: `/build --react --components --auth`
- **Persona**: frontend
- **Thinking**: think
- **MCPs**: magic, c7
- **Description**: Create login, register, and password reset forms
- **Expected Outcome**: Responsive, accessible auth UI components

### 7. Security Hardening
- **Command**: `/improve --security --strict`
- **Persona**: security
- **Thinking**: think-hard
- **MCPs**: c7, seq
- **Description**: Implement rate limiting, CSRF tokens, secure headers
- **Expected Outcome**: All security measures in place and tested

### 8. Integration Testing
- **Command**: `/test --integration --e2e --auth`
- **Persona**: qa
- **Thinking**: think
- **MCPs**: pup, c7
- **Description**: Complete auth flow testing including edge cases
- **Expected Outcome**: All auth flows tested, edge cases covered

### 9. Performance Optimization
- **Command**: `/improve --performance --analyze`
- **Persona**: performance
- **Thinking**: think
- **MCPs**: c7, seq
- **Description**: Optimize auth queries, implement caching strategy
- **Expected Outcome**: Auth endpoints < 200ms response time

### 10. Documentation
- **Command**: `/document --api --user --auth`
- **Persona**: mentor
- **Thinking**: think
- **MCPs**: c7
- **Description**: Create API docs and user guides for authentication
- **Expected Outcome**: Complete auth documentation for devs and users

## Persona Validation

### Architect
- [ ] Clear separation between auth and business logic
- [ ] Scalable session management design
- [ ] Proper use of DDD bounded contexts
- [ ] Clean architecture principles followed
- [ ] Database design supports future requirements

### Security
- [ ] OWASP authentication guidelines followed
- [ ] Passwords hashed with bcrypt (min 10 rounds)
- [ ] JWT tokens properly signed and validated
- [ ] Rate limiting on all auth endpoints
- [ ] CSRF protection on state-changing operations
- [ ] Secure password reset flow
- [ ] Account enumeration prevention
- [ ] Proper session invalidation

### Frontend
- [ ] Accessible forms (WCAG 2.1 AA)
- [ ] Clear error messages and validation
- [ ] Loading states for all operations
- [ ] Mobile-responsive design
- [ ] Password strength indicator
- [ ] Social login buttons prominent

### Backend
- [ ] RESTful API design
- [ ] Proper HTTP status codes
- [ ] Comprehensive error handling
- [ ] Database transactions for critical operations
- [ ] Efficient queries with proper indexing
- [ ] Clean service layer abstraction

### QA
- [ ] Unit tests > 90% coverage
- [ ] Integration tests for all flows
- [ ] E2E tests for critical paths
- [ ] Edge case testing (invalid inputs, race conditions)
- [ ] Security testing (SQL injection, XSS)
- [ ] Performance tests under load

### Performance
- [ ] Auth endpoints < 200ms
- [ ] Database queries optimized
- [ ] Caching strategy implemented
- [ ] Connection pooling configured
- [ ] No N+1 query problems
- [ ] Minimal JWT token size

### Mentor
- [ ] Clear API documentation
- [ ] User guides with screenshots
- [ ] Developer setup instructions
- [ ] Common issues troubleshooting
- [ ] Architecture decision records
- [ ] Code examples provided

### Refactorer
- [ ] No code duplication
- [ ] SOLID principles followed
- [ ] Proper error handling patterns
- [ ] Consistent naming conventions
- [ ] No magic strings/numbers
- [ ] Clean dependency injection

### Analyzer
- [ ] Comprehensive logging strategy
- [ ] Error tracking integration
- [ ] Metrics for auth success/failure
- [ ] Debug mode for development
- [ ] Audit trail for security events
- [ ] Performance monitoring setup