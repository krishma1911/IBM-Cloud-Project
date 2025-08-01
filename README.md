# AI-Powered LaTeX Diagram Generator for Academic Research

This project enables users to generate complex LaTeX diagrams, such as flowcharts, ER diagrams, and system architectures, by simply providing natural language instructions. The system uses foundation models hosted on IBM watsonx.ai to convert textual prompts into LaTeX (TikZ) code with high accuracy.

## Project Overview

- Converts plain English diagram descriptions into LaTeX TikZ code.
- Utilizes agentic AI to understand instructions and generate precise diagram structures.
- Supports academic use cases by automating technical diagram creation.
- Deployed and executed using IBM Cloud services.

## Tools and Technologies Used

- **IBM watsonx.ai** – for model deployment and execution
- **Granite-3-3-8B-Instruct Model** – for natural language to LaTeX code generation
- **IBM Cloud Object Storage** – for storing generated files and outputs
- **IBM watsonx.ai Runtime** - for processing and providing CPU,RAM,etc

  ## Instruction given to LaTeX Agent - You are a LaTeX diagram generator specialized in converting natural language descriptions into TikZ code.

- When a user describes a diagram (e.g., "a binary tree with 3 nodes"), respond only with:
   - TikZ code inside triple backticks
   - A brief summary of what the diagram will look like
- The TikZ code should be syntactically correct and optimized for academic papers.
- Support commands like "Add a node", "Make arrow red", etc.
- Do not include LaTeX document headers unless requested.


## Result

The system significantly reduces manual effort in creating academic diagrams, enabling researchers to focus more on content than formatting, while maintaining LaTeX-level quality and consistency.

## Screnshots 
![RESULTS] <br><br>
<img width="918" height="599" alt="Screenshot 2025-07-31 113038" src="https://github.com/user-attachments/assets/0392ca19-2e64-4905-a880-eaf1827297fa" />
<img width="870" height="611" alt="Screenshot 2025-07-31 113053" src="https://github.com/user-attachments/assets/e292a6ee-f2c0-4249-b66d-00572c3b412e" />
<img width="882" height="619" alt="Screenshot 2025-07-31 113113" src="https://github.com/user-attachments/assets/d7a09a9d-4d18-4d39-84a2-ab4f11950458" />
<img width="931" height="612" alt="Screenshot 2025-07-31 113124" src="https://github.com/user-attachments/assets/0dc9516f-9ea6-4a7c-a0fa-ebe85feac3f1" /> <br><br>
![VALIDATION OF OUTPUT]
<img width="1211" height="629" alt="Screenshot 2025-07-31 114526" src="https://github.com/user-attachments/assets/749af5eb-85ce-4efc-b9a4-f9623d09447e" />


## License

This project is developed for academic and educational purposes.
