def create_profile(name, title, email, learning, collaboration):
  """
  Creates a formatted GitHub profile.
  """

  profile = f"""
  ## {name}

  **{title}**

  **Contact:**
  * {email}

  **Currently Learning:**
  * {learning}

  **Looking for Collaboration:**
  * {collaboration}

  ---

  **Skills:**
  * Python
  * HTML
  * CSS
  * JavaScript (Basic)
  """

  return profile

# Get user input and print the profile
name = input("Enter your name: ")
title = input("Enter your title (e.g., ML/AI Engineer): ")
email = input("Enter your email address: ")
learning = input("What are you currently learning (e.g., Data Science)? ")
collaboration = input("What are you looking to collaborate on? ")

print(create_profile(name, title, email, learning, collaboration))


<!--
**AbdylGaniwu/AbdylGaniwu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
