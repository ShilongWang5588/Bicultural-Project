# Bicultural-Project

Welcome to this GitHub page for data analysis on a project with Professor Muniba Saleem that examines how social identity threats (eg. discrimination, media stereotypes) inflence bicultural (non-White first-thrid generation immigrants) students' willingness to avoid and approach White Americans. Mediating role of self-esteem as well as private and public collective esteem is examined. For reasons that this study has not gone published, the dataset on which this data analysis code is based and the results from the data analysis is not included here. Therefore, the code is for reference for scholars who would like to run data analysis regarding data cleaning, multiple linear regression, mediating effects, and moderating effects.



Variable explanation (For privacy issues, explanations for each variable are not provided but their functions are provided so that you can replace them with the variables in the dataset you would like to run analysis on):

Response variables (Y): avoiding behaviors, confronting behaviors, and approaching behaviors.
Predictor variables (X): media stereotypes, ethnic media exposure, American media exposure.
Control variable: generation （which specifies the generation of the each participant. The encoding of which is indicated at the beginning of the code, commented as "coding generation."）
Mediators： self-esteem, private perception, and public perception. 
Moderators ： personal experience discrimination and group experience of discrimination.

In the R markdown file I uploaded, there are some comments on my results. Please interpret them based on the results you run on your dataset; otherwise they would not make sense.

In my code where I run mediation and moderation, I used a self-defined function created by Professor Hayes. Reference: Hayes, A.F. (2013). Introduction to mediation, and conditional process analysis: A regression-based approach. Guildford Press.
