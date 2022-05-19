using System.IO;
 
namespace Calculadora
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }
 
        double a;
        double b;
        string c;
 
        private void btn1_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "1";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "1" ;
            }
        }
 
        private void btn2_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "2";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "2";
            }
        }
 
        private void btn3_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "3";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "3";
            }
        }
 
        private void btn4_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "4";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "4";
            }
        }
 
        private void btn5_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "5";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "5";
            }
        }
 
        private void btn6_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "6";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "6";
            }
        }
 
        private void btn7_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "7";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "7";
            }
        }
 
        private void btn8_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "8";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "8";
            }
        }
 
        private void btn9_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "9";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "9";
            }
        }
 
        private void btn0_Click(object sender, EventArgs e)
        {
            if (txtpantalla.Text == "")
            {
                txtpantalla.Text = "0";
            }
            else
            {
                txtpantalla.Text = txtpantalla.Text + "0";
            }
        }
 
        private void btndivision_Click(object sender, EventArgs e)
        {
            a = Convert.ToDouble(this.txtpantalla.Text);
            c = "/";
            this.txtpantalla.Clear();
            this.txtpantalla.Focus();
        }
 
        private void btnmultiplicacion_Click(object sender, EventArgs e)
        {
            a = Convert.ToDouble(this.txtpantalla.Text);
            c = "*";
            this.txtpantalla.Clear();
            this.txtpantalla.Focus();
        }
 
        private void btnresta_Click(object sender, EventArgs e)
        {
            a = Convert.ToDouble(this.txtpantalla.Text);
            c = "-";
            this.txtpantalla.Clear();
            this.txtpantalla.Focus();
        }
 
        private void btnsuma_Click(object sender, EventArgs e)
        {
            a = Convert.ToDouble(this.txtpantalla.Text);
            c = "+";
            this.txtpantalla.Clear();
            this.txtpantalla.Focus();
        }
 
        private void btnpunto_Click(object sender, EventArgs e)
        {
            if (this.txtpantalla.Text.Contains('.')==false)
            {
                this.txtpantalla.Text = this.txtpantalla.Text + ".";
            }
 
 
        }
 
        private void btnigual_Click(object sender, EventArgs e)
        {
            b = Convert.ToDouble(this.txtpantalla.Text);
            switch (c)
            {
                case "+":
                    this.txtpantalla.Text  = Convert.ToString (b + a);
                    break;
 
                case "-":
                    this.txtpantalla.Text = Convert.ToString(b - a);
                    break;
 
                case "*":
                    this.txtpantalla.Text = Convert.ToString(b * a);
                    break;
 
                case "/":
                    this.txtpantalla.Text = Convert.ToString(b / a);
                    break;
            }
 
 
        }
 
        private void btnprint_Click(object sender, EventArgs e)
        {
            StreamWriter Archivo = new StreamWriter("Ruta\\archivo.txt");
            Archivo.WriteLine("Operaciones: " + a + c + b + "=" + this.txtpantalla.Text);
            Archivo.Flush();
            Archivo.Close();
 
            System.Diagnostics.Process.Start("Ruta\\archivo.txt");
        }
 
        private void btnlimpiar_Click(object sender, EventArgs e)
        {
            a = Convert.ToDouble("");
            b = Convert.ToDouble("");
            this.txtpantalla.Text = "";
 
        }
    }
}
