# Royal-Car-Motor
We are normlly creating a database to record allits sales and purchases to avoid fraud.
 string[] GirlName = new string[15];
            int index = 0;
 string searchvalue = txtname.Text;
            bool found = false; //will be changed to true if value found otherwise shall remain false
            int first = 0; //set index of first array elements to array size -1
            int last = GirlName.Length; //set index of last array elements to array size -1
            int middle = 0; //store index of middle elements
            //Loop as long as we have not found the element searched for and there are still elements to be searched for
            while((found == false) && (first <= last))
