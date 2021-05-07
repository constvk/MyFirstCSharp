# MyFirstCSharp ( C# )

> TextBox And MessageBox

<img src="https://media.discordapp.net/attachments/839163987484606495/840097164947750922/C.png">

# CODE:
```cs
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            textBox1.Text = "Olá Mundo! Hello World! - github.com/constvk";
            MessageBox.Show("My Fist C# !");

        }

        private void label1_Click(object sender, EventArgs e)
        {

        }
    }
}
```
