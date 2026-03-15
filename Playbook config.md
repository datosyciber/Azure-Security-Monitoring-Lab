To access the playbook settings panel, go to the Settings > Automation section in your workspace. There, you’ll see a link that takes you directly to the section in the Defender portal where you can create a new playbook.

![imagen](https://github.com/user-attachments/assets/3ee96937-f944-4db1-8ecc-ee923931bf9c)

In the “Create” option, select “Create with incident trigger” so that it runs every time the detection rule generates an incident. Once in the “Logic Application Designer” panel, you'll see the workspace ready for creating ‘command’ or “process” blocks that will execute sequentially. In my case, I configured the playbook so that after an incident is generated, I receive an email with relevant information about it and a direct link to the incident page.
