# Docker & Kubernetes: The practical guide

- [Docker \& Kubernetes: The practical guide](#docker--kubernetes-the-practical-guide)
  - [Sections](#sections)
    - [Section 1: Getting Started](#section-1-getting-started)
      - [References](#references)
      - [Notes](#notes)
  - [References](#references-1)

## Sections

### Section 1: Getting Started

#### References

- [Slide 1 - Getting Started](./resource/slides/01-slide-getting-started.pdf)

#### Notes

- A Container is a standardized unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

  > Container = A package of code + Dependencies to run that code

- Docker is a container technology: A tool for creating and managing containers.

- Why do we need a Container?

  - The problems:
    - Different development and production environments
    - Different development environments within the team/company
    - Clashing tools, versions, and dependencies between different projects
  - Solution:
    - Expect the same environments for development and production.
    - Share a common development environment/setup
    - Don't want to uninstall and reinstall local dependencies and runtimes all the time

- Virtual Machines and Container

  | Container                                             | Virtual Machines                                     |
  | ----------------------------------------------------- | ---------------------------------------------------- |
  | Low impact on OS, very fast, minimal disk space usage | Bigger impact on OS, slower, higher disk space usage |
  | Sharing, re-building and distribution is easy         | Sharing, re-building and distribution is hard        |
  | Encapsulation apps/environments                       | Encapsulation "whole machines"                       |

## References

- [Udemy course](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)
