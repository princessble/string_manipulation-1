# String Manipulations – Practice 1 (UiPath)

This project shows how to use common string methods to extract information from text and print it in a different format. It uses `Format`, `Join`, `IndexOf`, `Split`, and `Substring` in a simple workflow.&#x20;

---

## Project info

* **Name:** String Manipulations practice 1&#x20;
* **Entry point:** `Main.xaml`&#x20;
* **Studio version:** 25.0.172.0&#x20;
* **Language:** Visual Basic (VB) expressions&#x20;
* **Output type:** Process (Windows)&#x20;
* **Project version:** 1.0.0&#x20;

---

## Dependencies

* `UiPath.System.Activities` **25.6.1** (auto-restore on open).&#x20;

---

## What it does

* Reads a text message.
* Pulls out the course part from the first sentence.
* Pulls out the list of places from the second sentence.
* Shows the result in a **Message Box** using `String.Format` and `String.Join`.
  (The exact parsing logic follows the project description and uses the methods listed above.)&#x20;

---

## How to run

1. Open **UiPath Studio 25.0.172** or later.&#x20;
2. **Open** the project folder (the one containing `project.json`).
3. Let Studio restore dependencies.&#x20;
4. Open `Main.xaml`.
5. Click **Run**.

> The workflow is designed as a standard attended workflow that shows UI (Message Box). The project marks `requiresUserInteraction` as true.&#x20;

---

## Notes

* The project targets **Windows** and uses the **NewtonsoftJson** serializer for workflows.&#x20;
* If you want to adapt it for C# expressions, create a C# project and port the VB expressions accordingly (logic stays the same). (The current project is VB.)&#x20;

---

## Folder layout

```
.
├─ Main.xaml
├─ project.json
└─ README.md
```

---

## Versioning

* **Project:** 1.0.0 (initial public version).&#x20;

---

## License

Add your preferred license here (e.g., MIT).
