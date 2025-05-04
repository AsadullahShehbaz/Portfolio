# **Building a Portfolio**

We will use mkdocs for building a portfolio.Mkdocs is a static site generator that is geared towards project documentation .It is written in python and uses the Jinja2 templating engine .Mkdoc is easy to use and has a lot of features that make it a good choice for building a portfolio.

Link to the documentation is [here](https://mkdocs.org/getting-started/)

## **1.Install mkdocs**
```bash
conda create -n mkdocs python=3.10 -y
conda activate mkdocs
pip install mkdocs
```

## **2.Create a new mkdocs Project**
```bash
mkdocs new Asadullah_Portfolio
cd Asadullah_Portfolio
```

## **3.Run the Development Server**

> This is how you can specify the  port and host
```bash
mkdocs serve -a 127.0.0.1:8501
```

## **4. Build the Project**
```bash
 mkdocs build
```
## **5. Change Theme**
> You can install a new theme and update it in mkdocs.yml: 
``` bash
pip install mkdocs-material 
```
> Update mkdocs.yml:
```yml
theme:
  name: material
```

## **6. Add Pages**
> You can add new pages to your site by modifying mkdocs.yml:
``` yml
nav: 
  - Home: index.md
  - Blog: blog.md
  - Projects: project.md
  
```

## **7. Auto Resume Prompt** 
Press `Ctrl+I` and Paste it
> Build this page Using emojis and other information needed to make my resume as a data scientist.Show me the template

## **8. Auto About ME Prompt** 
Press `Ctrl+I` and Paste it
> Create the best possible about me page, I am working as a data scientist with Codanics website to practise on differenet projects . Please use emojis and Pakistani Tarka style.
## **8. Auto mkdocs.yml Prompt(For GPT)** 
Press `Ctrl+I` and Paste it
> Great, Can you please create a mkdocs.yml file content for me to make the best possible design for data scientisits and Al developers here is the crucial information.