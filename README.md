# Lab M5.01 - First GitHub Actions Pipeline

**Cloud Engineering Bootcamp - Week 5, Day 1**  
**Module:** Cloud Automation & CI/CD

## 📋 Lab Overview

In this lab, you'll create your first GitHub Actions workflow to automate testing and deployment tasks. You'll learn how to set up CI/CD pipelines, configure triggers, and implement automated workflows.

## 🎯 Learning Objectives

- Create and configure GitHub Actions workflows
- Understand YAML workflow syntax
- Implement automated testing and deployment
- Work with GitHub Actions runners and environments
- Configure workflow triggers and conditions

## 📁 Repository Structure

```
ce-lab-first-github-actions-pipeline/
├── .github/
│   └── workflows/
│       ├── ci.yml           # Continuous Integration workflow
│       └── deploy.yml       # Deployment workflow
├── src/
│   └── app.py              # Sample application
├── tests/
│   └── test_app.py         # Test suite
├── README.md               # This file
└── requirements.txt        # Python dependencies
```

## ✅ Submission Requirements

1. **Complete GitHub Actions workflows**
   - CI workflow with automated testing
   - Deployment workflow with environment configuration

2. **Working application**
   - Sample application code
   - Passing test suite

3. **Documentation**
   - README with workflow explanations
   - Comments in workflow files

4. **Successful workflow runs**
   - Screenshots or links to successful runs
   - Evidence of automated testing

## 🎓 Grading Rubric

| Criteria | Points | Description |
|----------|--------|-------------|
| **Workflow Configuration** | 30 | Properly configured CI/CD workflows with correct syntax |
| **Automated Testing** | 25 | Implemented automated test execution |
| **Deployment Setup** | 25 | Working deployment workflow with proper triggers |
| **Documentation** | 10 | Clear README and workflow documentation |
| **Workflow Success** | 10 | Evidence of successful workflow execution |
| **Total** | 100 | |

## 💡 Tips

- Start with a simple workflow and add complexity gradually
- Test workflows with manual triggers first
- Use GitHub's workflow syntax documentation
- Check the Actions tab for workflow run details
- Use secrets for sensitive information

## 📚 Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Workflow Syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)

## 🚀 Submission

Submit your repository URL through the course platform. Ensure your repository is accessible to instructors.

**Repository URL Format:** `https://github.com/YOUR_USERNAME/ce-lab-first-github-actions-pipeline`
