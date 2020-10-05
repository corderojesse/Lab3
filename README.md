# Lab3
Where I sorted a LinkedList
//THe way I made my code was that I chose a single artist per alphabet and placed it within a linkedlist, then I imported a scanner to allow the user to input an alphabet and get the corresponding artist. 





import java.util.Collections;
import java.util.LinkedList;
import java.util.Scanner;


public class artistList {

	public static void main(String[] args) {
		 
		//Creating Linked Artist List
		LinkedList artistList = new LinkedList();
		
		//Adding artist to the list
		artistList.add("Amy Winehouse");
		artistList.add("Billy Idol");
		artistList.add("Cream");
		artistList.add("Dr.Dre");
		artistList.add("Elton John");
		artistList.add("Frank Sinatra");
		artistList.add("Ghostface Killah");
		artistList.add("Hayley Williams");
		artistList.add("Ice Cube");
		artistList.add("JAY-Z");
		artistList.add("Kid Cudi");
		artistList.add("Led Zeppelin");
		artistList.add("Mos Def");
		artistList.add("Nas");
		artistList.add("OutKast");
		artistList.add("Paramore");
		artistList.add("Queen");
		artistList.add("Raekwon");
		artistList.add("Snoop Dogg");
		artistList.add("The Doors");
		artistList.add("Usher");
		artistList.add("Verve");
		artistList.add("Wu-Tang Clan");
		artistList.add("XXXTENTACION");
		artistList.add("Young Thug");
		artistList.add("Zedd");
		
		//Sorting List Alphabetical order
		Collections.sort(artistList);
		
		//Making a scanner
		Scanner alphabet = new Scanner(System.in);
		
		System.out.println("Enter a letter of the alphabet to search for artist: ");
		String a = alphabet.nextLine();
		
		
	
		
		System.out.println("Artist: "); 
		
		
		//Adding songs to the corresponding artist 
		if (a.equals("a"))
		{
			
		
			System.out.println(artistList.get(0));
			
			System.out.println("Their best song: 'In My Bed' (2003)");
			System.out.println("");
			
			
			
			
		}
		
			
		if( a.equals("b"))
		{
				
				
				System.out.println(artistList.get(1));
				
				System.out.println("Their best song: 'Flesh For Fantasy' (1983)");
				System.out.println("");
			
		}
		
		if (a.equals("c"))
		{
			
			
			System.out.println(artistList.get(2));
			
			System.out.println("Their best song: 'White Room' (1968)");
			System.out.println("");
		

		}
		
		if (a.equals("d")) 
		{
			
			
			System.out.println(artistList.get(3));
			
			System.out.println("Their best song: 'Some L.A. N****z' (feat. King T, Kokane, Knoc-turn'al, MC Ren, Defari, Xzibit, Hittman,T. B.) (2001)");
			System.out.println("");
		}
		
		if (a.equals("e"))
		{
			
			
			System.out.println(artistList.get(4));
			
			System.out.println("Their best song: 'I Think I'm Going to Kill Myself' (1972)");
			System.out.println("");
		

		}
		if (a.equals("f"))
		{
			
			
			System.out.println(artistList.get(5));
			
			System.out.println("Their best song: 'That's Life' (1966)");
			System.out.println("");
		

	}
		if (a.equals("g"))
		{
			
			
			System.out.println(artistList.get(6));
			
			System.out.println("Their best song: 'Cherchez la ghost (feat.U-God)' (2000)");
			System.out.println("");
		

	}
		if (a.equals("h"))
		{
			
			
			System.out.println(artistList.get(7));
			
			System.out.println("Their best song: 'The Only Exception' (2009)");
			System.out.println("");
		

	}
		if (a.equals("i"))
		{
			
			
			System.out.println(artistList.get(8));
			
			System.out.println("Their best song: 'It Was a Good Day' (1992)");
			System.out.println("");
		

	}
		if (a.equals("j"))
		{
			
			
			System.out.println(artistList.get(9));
			
			System.out.println("Their best song: 'My 1st Song' (2003)");
			System.out.println("");
		

	}
		if (a.equals("k"))
		{
			
			
			System.out.println(artistList.get(10));
			
			System.out.println("Their best song: 'Mr. Rager' (2010)");
			System.out.println("");
		

	}
		if (a.equals("l"))
		{
			
			
			System.out.println(artistList.get(11));
			
			System.out.println("Their best song: 'Stairway to Heaven' (1971)");
			System.out.println("");
		

	}
		if (a.equals("m"))
		{
			
			
			System.out.println(artistList.get(12));
			
			System.out.println("Their best song: 'Ms. Fat Booty' (1999)");
			System.out.println("");
		

	}
		if (a.equals("n"))
		{
			
			
			System.out.println(artistList.get(13));
			
			System.out.println("Their best song: 'Made You Look' (2002)");
			System.out.println("");
		

	}
		if (a.equals("o"))
		{
			
			
			System.out.println(artistList.get(14));
			
			System.out.println("Their best song: 'Gasoline Dreams' (with Khujo Goodie) (2000)");
			System.out.println("");
		

	}
		if (a.equals("p"))
		{
				System.out.println(artistList.get(15));
			
			System.out.println("Their best song: 'Monster' (2011)");
			System.out.println("");
		}
		
		if (a.equals("q"))
		{
				System.out.println(artistList.get(16));
			
			System.out.println("Their best song: 'Who Wants To Live Forever' (1986)");
			System.out.println("");
		}
		
		if (a.equals("r"))
		{
				System.out.println(artistList.get(17));
			
			System.out.println("Their best song: 'Rainy Dayz' (2001)");
			System.out.println("");
		}
		if (a.equals("s"))
		{
				System.out.println(artistList.get(18));
			
			System.out.println("Their best song: 'Crazy' (feat. Nate Dogg) (2006)");
			System.out.println("");
		}
		if (a.equals("t"))
		{
				System.out.println(artistList.get(19));
			
			System.out.println("Their best song: 'When the Music's Over' (1970)");
			System.out.println("");
		}
		if (a.equals("u"))
		{
				System.out.println(artistList.get(20));
			
			System.out.println("Their best song: 'You Make Me Wanna' (1997)");
			System.out.println("");
		}
		if (a.equals("v"))
		{
				System.out.println(artistList.get(21));
			
			System.out.println("Their best song: 'Bitter Sweet Symphony' (1997)");
			System.out.println("");
		}
		if (a.equals("w"))
		{
				System.out.println(artistList.get(22));
			
			System.out.println("Their best song: 'Tearz' (1993)");
			System.out.println("");
		}
		if (a.equals("x"))
		{
				System.out.println(artistList.get(23));
			
			System.out.println("Their best song: 'Jocelyn Flores' (2017)");
			System.out.println("");
		}
		if (a.equals("y"))
		{
				System.out.println(artistList.get(24));
			
			System.out.println("Their best song: 'High' (feat. Elton John) (2018)");
			System.out.println("");
		}
		if (a.equals("z"))
		{
				System.out.println(artistList.get(25));
			
			System.out.println("Their best song: 'Stay The Night' (2012)");
			System.out.println("");
		}
		
		System.out.println("Spotify Artist List: ");
		
		
		
		//In order to print list vertically
	for(int i=0;i<artistList.size();i++)
		
	{
		
			    System.out.println( artistList.get(i));
	 }

	}

}
