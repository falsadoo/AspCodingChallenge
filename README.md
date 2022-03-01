**ASP .Net 6 Coding Challenge**
For this project we need to create a Rest API with No views for our Command model. The command Model is already configured as the following:
 

    public class Command
    {
        [Key]
        [Required]
        public int Id { get; set; }

        [Required]
        public string HowTo { get; set; }
        
        [Required]
        public string Line { get; set; }
        
        [Required]
        public string Platform { get; set; }
    }
   We have also have one controller with the all CRUD operation defined but not all is implemented.
   **Requirements** 
   **MockCommanderRepo**
   In the project mock repository class we need to implement all the missing CRUD operations. 
   ** CommandsController**
   In this controller we need to implement all the missing CRUD operations endpoints. Please make sure to handle users errors correctly.
   **Command Model / DTO Validation**
   We need to add the following validations rules:
 - **HowTo** need a min value of 4 characters and max value of 250 characters.
 - **Platform** will only have 4 characters no more or less e.g. MSSP. 

**Please clone this Repo and create a branch with your name**
