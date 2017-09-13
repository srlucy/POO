class for4
{
	public static void main(String args[])
	{
		int aum = 10, sum = 0, gen = 0;

			for (int i = 1; i <=5; ++i)
			{
				for(int j = 1; j <=5; ++j)
				{
			
					sum = aum + sum;

					System.out.println(aum+ "\t");
					aum += 10;
				}
				gen = sum + gen;
				System.out.println(sum);
				sum = 0;
				System.out.println("\n");
			}
		System.out.println("El gran total es" + gen);
		System.out.println("Hasta Luego");
	}
}
