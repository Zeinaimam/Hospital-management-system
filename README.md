using System;

public class patient
{
	public int Id { get; set; }	
	public string Name { get; set; }
	public string Gender { get; set; }
    public int Age { get; set; }
    public string Illness { get; set; }

    public patient(int Id, string Name, string Gender, int Age, string Illness)
	{
		this.Id = Id;
		this.Name = Name;	
		this.Gender = Gender;	
		this.Age = Age;	
		this.Illness = Illness;

	}
}
piblic class doctor 
