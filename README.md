# doc-agent-installer
Local AI document agent with installer
Version: 1.0
Developer: Marin Benson

Overview
--------
Doc Agent is a local AI-powered assistant that lets you query and analyze PDF, Word, and Excel documents stored on your computer. It runs entirely offline and uses embedded AI models to provide context-aware responses to your questions.

Installation
------------
1. Run the Doc Agent installer (.exe file).
2. Follow the prompts to complete installation.
3. By default, the app installs to:
   C:\Program Files (x86)\DocAgent\
4. A desktop shortcut will be created for easy access.

Getting Started
---------------
1. Place your documents into the following folder:
   C:\Program Files (x86)\DocAgent\documents\
   (or the corresponding path if you installed elsewhere)

   Supported formats:
   - .pdf (PDF files)
   - .docx (Word documents)
   - .xlsx (Excel files)

2. Double-click the Doc Agent shortcut to launch.

3. Use the available commands when prompted:

   [index/query/remember/list/edit/delete/exit]

   - index   = scan and process all files into searchable memory
   - query   = ask a question about your documents
   - remember = add a fact manually (include #example to create easily searchable facts)
   - list    = view all memory
   - edit    = change stored memory text
   - delete  = remove a memory entry
   - exit    = close the app

Usage Notes
-----------
- Always run `index` after adding new files.
- You can ask questions like:
    Do the documents say anything about ice cream?
    If so, what is the author's favourite ice cream flavour and why?
- Make sure Excel files are closed before indexing.
- Skip files starting with `~$` or temporary names.

Performance Tips
----------------
- Works best on machines with a GPU.
- Large documents may take longer to index.
- For best results, ensure documents are well-structured.

Support
-------
For help, contact Marin at marin.benson@infrastream.au.

