# Curriculum98
private String t, d, de;
    public Curriculum(String title, String description, String department)
    {
        t = title;
        d = description;
        de = department;
        
    }
    public String getTitle()
    {
        return t;
    }
    public String getDescription()
    {
        return d;
    }
    public String getDepartment()
    {
        return de;
    }
    
    public String toString()
    {
        return "Title: " + t + ", \nDescription: "+ d +", \nDepartment: " + de;
    }
    
# Main
    Math MVC = new Math("Multi-Variable Calculus", "Hard Math", "Math", "H", "Semus");
		History Psychology = new History("AP Psycology", "Hard History", "History", "AP", "LaSure");
		English English = new English("English 4A", "Medium English", "English", "A", "Shjarback");
        
        // Printing out classes established
        System.out.println(MVC);
        MVC.getTeacher();
        MVC.getLevel();
        System.out.println();
        
        System.out.println(Psychology);
        Psychology.getTeacher();
        Psychology.getLevel();
        System.out.println();

        System.out.println(English);
        English.getTeacher();
        English.getLevel();
        System.out.println();
  
  # Math
  public String lev;
	public String teach;
	public Math(String title, String description, String department, String level, String teacher)
  {
		  super(title, description, department);
		  lev = level;
		  teach = teacher;
	 }
	 public void getLevel()
   {
	    System.out.println(lev);
	 }
	 public void getTeacher()
   {
	  	 System.out.println(teach);
	 }
   
# History
  public String lev;
	public String teach;
	public History(String title, String description, String department, String level, String teacher)
  {
		super(title, description, department);
		lev = level;
		teach = teacher;
	}
	 public void getLevel()
  {
		 System.out.println(lev);
  }
	 public void getTeacher()
  {
		 System.out.println(teach);
  }

# English
  public String lev;
	public String teach;
	public English(String title, String description, String department, String level, String teacher)
  {
		super(title, description, department);
		lev = level;
		teach = teacher;
	}
	 public void getLevel()
  {
		 System.out.println(lev);
	}
	 public void getTeacher()
  {
		 System.out.println(teach);
	,}
