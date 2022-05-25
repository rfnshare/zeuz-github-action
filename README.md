# Python scripts in GitHub Actions

Learn how to Rrn Python scripts on GitHub Actions! This allows you to handle logic that might be a bit more complex, like setting conditional behavior based on results.

Although GitHub actions is powerful as-is, it can get complicated when consuming inputs from other sources like an HTTP request providing JSON output.

Imagine a scenario where, depending on the JSON output of an HTTP request you have to do an API call. You might be able to do this with a specialized action or workflow, but with Python it might be easier.

<!---
The full video is available on [YouTube](https://www.youtube.com/playlist?list=PLd5aRIS7MwjnS0tD_76sWMFVAxKaIcFWq), and the full course is also available on the [O'Reilly platform](https://learning.oreilly.com/videos/python-dictionaries-course/50136VIDEOPAIML/)

[![O'Reilly](https://learning.oreilly.com/covers/urn:orm:video:50136VIDEOPAIML/400w/)](https://learning.oreilly.com/videos/python-dictionaries-course/50136VIDEOPAIML/ "Deploy Containerized Apps on Azure")
> 🎥 Click the image above to access the full course on O'Reilly

-->


# Table of Contents

- [📚 Course Content](#course-content)
- [🎯Learning Objectives](#learning-objectives)
- [💡 Useful Resources](#useful-resources)



# Course Content

The easiest way of going through the full course is using the [O'Reilly platform](https://learning.oreilly.com/videos/python-dictionaries-course/50136VIDEOPAIML/) but you can start here as well and on [YouTube](https://youtu.be/Wu7j8z4B-1Y).


1. [Create a GitHub Action YAML file](./.github/workflows/script.yml)
1. [Add a Python file](./.github/workflows/example.py)
1. [Create a repository secret](settings/secrets/actions)
1. [Manually trigger your workflow](actions)


## Learning Objectives

In this course you will learn:

- How to run a Python script with GitHub Actions
- Create a Python script that can be executed from an Action
- Consume Action Secrets in the Python script
- Explore other ways to install dependencies  if needed


# Useful Resources

- [GitHub repository with sample code](https://github.com/alfredodeza/python-action)
- [Python dictionaries Learn Module](https://docs.microsoft.com/learn/modules/python-dictionaries/?WT.mc_id=academic-0000-alfredodeza)
- [Minimal Python book](https://www.amazon.com/Minimal-Python-efficient-programmer-onemillion2021-ebook/dp/B0855NSRR7)
- [Free Azure Certification for Students](https://docs.microsoft.com/learn/certifications/student-training-and-certification?WT.mc_id=academic-0000-alfredodeza)
- [Python for Beginners Learn Path](https://docs.microsoft.com/learn/paths/beginner-python/?WT.mc_id=academic-0000-alfredodeza)

