---
layout : post
title : Computer codes
categories : project 
---
We made codes here's an example:
               
                Console.WriteLine("How many children are there? ");
                int children = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("How many sweets do they each have? ");
                int sweets = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("How many ducks were there?");
                int ducks = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("How many sweets did each child give each duck? ");
                int sweetGiven = Convert.ToInt32(Console.ReadLine());

                Console.WriteLine(@"There were " + children + " children each with a bag containing " + sweets+
                    "sweets. They walked past " + ducks + " ducks. Each child gave " + sweetGiven + " sweets "
                    + "to each of the ducks and ate one themself. They decided to put the rest into a pile.");
                Console.WriteLine("They counted the pile and found it contained " + ((sweets * children) - (ducks * sweetGiven)) + " sweets.");
                
                Console.ReadLine()
