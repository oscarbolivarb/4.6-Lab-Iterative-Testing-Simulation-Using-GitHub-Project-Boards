# 4.6-Lab-Iterative-Testing-Simulation-Using-GitHub-Project-Boards
This lab showed how software testing can change as the system grows. For example, in the beginning the testing process focused on unit-level checks, such as verifying if the PasswordHasher class worked correctly and if the AuthenticationService accepted valid login credentials. 

Since the system was still simple it focused on making sure that the individual components would work correctly by itself. By adding additional features the testing process became more complex, especially when the SessionManager and the ProfileService components started working together with the authentication system. 

Here is where testing became more important and if there was a problem in one component then it could affect other parts of the system. For example, the login behavior, sessions and profile updates. 

By the final iteration, the main focus shifted towards regression testing and validating the complete user workflow. Since multiple features have already been added it became more important to make sure that the new updates did not break functionality from the ones that were already working. For example, testing full workflows such as login, logout and profiles. This helped verify that the system worked correctly from the user’s point of view. 

This type of testing progression supports continuous delivery because testing happens throughout development instead of only being at the end. By testing the system continuously as it grows, any issue can be found earlier and the software becomes more stable as well as more reliable as new features are added later. 

References 

Baresi, L. & Pezze, M. (2006). An Introduction to Software Testing. ScienceDirect. https://doi.org/10.1016/j.entcs.2005.12.014
Hellmann, T. D., Sharma, A., Ferreira, J. & Maurer, F. (2012). Agile Testing: Past, Present, and Future -- Charting a Systematic Map of Testing in Agile Software Development. IEEE. https://doi.org/10.1109/Agile.2012.8

