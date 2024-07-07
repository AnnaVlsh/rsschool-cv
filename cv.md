# Voiloshnikova Anna
---

## Contacts
**Phone:** +7(913)208-22-49

**Email:** LuoAmog@gmail.com

**Telegram:** @AnnaVlsh

**GitHub:** [AnnaVlsh](https://github.com/AnnaVlsh)

---

## Education
Incomplete higher education: Siberian State University of Telecommunications and Informatics

---
## Skills
* Figms
* HTML/CSS
* C# (Basic level)
* Git/GitHub
* English A1

---
## Code example

```
static double[,] ReadMatrix(string file)
        {
            string[] lines = File.ReadAllLines(file);
            int rows = lines.Length;
            int cols = lines[0].Split(' ').Length;
            double[,] matrix = new double[rows, cols];

            for (int i = 0; i < rows; i++)
            {
                string[] values = lines[i].Split(' ');
                for (int j = 0; j < cols; j++)
                {
                    matrix[i, j] = double.Parse(values[j]);
                }
            }
```
