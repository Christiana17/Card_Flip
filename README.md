using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Card_Flip_Application
{
    public partial class MainForm : Form
    {
        public MainForm()
        {
            InitializeComponent();
        }

        private void ShowBackButton_Click(object sender, EventArgs e)
        {

            CardBackPictureBox.Visible = true;
            CardFacePictureBox.Visible = false;
        }

        private void ShowFaceButton_Click(object sender, EventArgs e)
        {
            CardBackPictureBox.Visible = false;
            CardFacePictureBox.Visible = true;
        }
    }
}
