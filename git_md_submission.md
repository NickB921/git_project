md\_project\_submission
================
Nick Bowe
9/23/2021

``` r
setwd("C:\\Users\\17152\\Documents\\")
read.csv("input.csv")
```

    ##                              name                     position
    ## 1                 David H. Abbott                    Professor
    ## 2              Alaa A Abd-Elsayed        Assoc Professor (Chs)
    ## 3                 Faisal Abdullah                    Professor
    ## 4            Abraham Olufunmilola          Assistant Professor
    ## 5                 Samantha Abrams               Assoc Lecturer
    ## 6                    Lyn Abramson                    Professor
    ## 7                   Lindsay Acker                     Lecturer
    ## 8                 Steven Ackerman                    Professor
    ## 9          Peter Gabriel Adamczyk          Assistant Professor
    ## 10         Angel Adames-Corraliza          Assistant Professor
    ## 11                    Aeron Adams           Clinical Asst Prof
    ## 12                    Megan Adams           Asst Faculty Assoc
    ## 13                   Sarah Adcock          Assistant Professor
    ## 14         Rebecca Lynn Addington              Senior Lecturer
    ## 15                    Fenaba Addo          Associate Professor
    ## 16                   Sandra Adell                    Professor
    ## 17                     Aboud Affi   Clinical Adjunct Professor
    ## 18               Priyanka Agarwal          Assistant Professor
    ## 19                  Robert Agasie        Instrmt Innovator/Ins
    ## 20                   Adeola Agoke           Asst Faculty Assoc
    ## 21           Paul Gerald Ahlquist                    Professor
    ## 22                   Jameel Ahmad              Senior Lecturer
    ## 23                    Nihal Ahmad                    Professor
    ## 24                Azam Syed Ahmed        Assoc Professor (Chs)
    ## 25                     Jaerin Ahn          Assoc Faculty Assoc
    ## 26                        Sue Ahn                    Professor
    ## 27                    Yeohyun Ahn          Assistant Professor
    ## 28         Sarah Elizabeth Ahrens          Clinical Assoc Prof
    ## 29                    Albert L Ai           Visiting Asst Prof
    ## 30                Jeffrey P Aiken           Adjunct Instructor
    ## 31                   Naoki Aizawa          Assistant Professor
    ## 32                   Vivek Ajmani          Assoc Faculty Assoc
    ## 33                  Aditya Akella                    Professor
    ## 34                  David Al-Adra          Assistant Professor
    ## 35                 Awni M Al-Subu         Asst Professor (Chs)
    ## 36                 Oguzhan Alagoz                    Professor
    ## 37                  Elaine Alarid                    Professor
    ## 38                Samer N Alatout          Associate Professor
    ## 39               Aws Albarghouthi           Assitant Professor
    ## 40                   Craig Albers          Associate Professor
    ## 41                   Laura Albert                    Professor
    ## 42         Mark Richard Albertini                    Professor
    ## 43          Mercedes Alcala Galan          Associate Professor
    ## 44                      Ray Aldag                    Professor
    ## 45             Simeon David Alder            Faculty Associate
    ## 46             Kayla Alessandrino          Clinical Instructor
    ## 47    Andrew Layfayette Alexander                    Professor
    ## 48               Angela Alexander            Faculty Associate
    ## 49            Lacey Ann Alexander           Clinical Asst Prof
    ## 50                  Shantel D Ali         Asst Prof Of Mil Sci
    ## 51               Syed Ekhteya Ali              Senior Lecturer
    ## 52              Martha W. Alibali                    Professor
    ## 53                  Reid S Alisch           Assitant Professor
    ## 54                 Caitilyn Allen                    Professor
    ## 55                    David Allen                    Professor
    ## 56                  Heather Allen          Associate Professor
    ## 57                     Matt Allen                    Professor
    ## 58              Monique Allewaert          Associate Professor
    ## 59                   Mark C Allie            Faculty Associate
    ## 60                 Araceli Alonso                 Dis Lecturer
    ## 61           Soh-Hyun Park Altino          Associate Professor
    ## 62                 Beth Altschafl            Faculty Associate
    ## 63                  Moses Altsech                     Lecturer
    ## 64                    Joy Altwies            Faculty Associate
    ## 65            Elizabeth E Alvarez           Clinical Asst Prof
    ## 66                 Saylin Alvarez              Senior Lecturer
    ## 67           Daniel Amador-Noguez          Associate Professor
    ## 68                     Kurt Amann          Associate Professor
    ## 69             Richard M. Amasino                    Professor
    ## 70         Felice Catherine Amato                     Lecturer
    ## 71                    Laila Amine          Associate Professor
    ## 72                   Paul Amsbary           Adjunct Assoc Prof
    ## 73                     Panduan An           Visiting Asst Prof
    ## 74                    Zhe Gigi An          Assistant Professor
    ## 75           Karthik Anantharaman          Assistant Professor
    ## 76             Pablo Ancos Garcia          Associate Professor
    ## 77               Claus E Anderson          Assistant Professor
    ## 78                 David Anderson                    Professor
    ## 79               David F Anderson                    Professor
    ## 80               Kathryn Anderson                     Lecturer
    ## 81                  Lori Anderson          Assistant Professor
    ## 82                  Mark Anderson          Assistant Professor
    ## 83                 Peter Anderson              Senior Lecturer
    ## 84            Richard A. Anderson                    Professor
    ## 85               Rozalyn Anderson          Associate Professor
    ## 86                  David R Andes                    Professor
    ## 87                Susan J Andreae          Assistant Professor
    ## 88          Christian G. Andresen          Assistant Professor
    ## 89                 Joseph Andrews       Mechanical Engineering
    ## 90                    Uri Andrews          Associate Professor
    ## 91             Anna Andrezejewski                    Professor
    ## 92                     Cecile Ane                    Professor
    ## 93                    Jean-Michel                    Professor
    ## 94                    Robert Anex                    Professor
    ## 95             Sigurd B. Angenent                    Professor
    ## 96   Hernan Lizardo Angula Bracho          Clinical Instructor
    ## 97                 Jennifer Angus                    Professor
    ## 98                   Calli Anibas          Assoc Research Spec
    ## 99                 Melissa Anibas           Clinical Asst Prof
    ## 100                    Umar Anjum          Research Specialist
    ## 101                    Erika Anna           Asst Faculty Assoc
    ## 102                Aseem Z Ansari                    Professor
    ## 103               Kathleen Antony         Asst Professor (Chs)
    ## 104              John Archambault             Assistant Dean/L
    ## 105          Thomas J. Archdeacon                    Professor
    ## 106                        BJ Ard          Assistant Professor
    ## 107                 Alina Arefeva          Assistant Professor
    ## 108                   Lisa Arendt          Assistant Professor
    ## 109                   Sandra Afra            Faculty Associate
    ## 110                  Dima Arinkin                    Professor
    ## 111             Grant W Armstrong          Associate Professor
    ## 112              Joshua Armstrong          Associate Professor
    ## 113          Kimberly Kegel Arndt  Clincical Adjunct Asst Prof
    ## 114                Michael Arnold                    Professor
    ## 115       Courtney Jeanne Arnoldy         Clincical Instructor
    ## 116                  Neeraj Arora                    Professor
    ## 117      Andrea C. Arpaci-Dusseau                    Professor
    ## 118       Remzi H. Arpaci-Dusseau                    Professor
    ## 119             Francisco Arriaga          Associate Professor
    ## 120     Sebastian I Arriola Apelo          Assistant Professor
    ## 121                  Emily Arthur          Associate Professor
    ## 122       Sophie Ann Aschenbrioch            Clincal Asst Prof
    ## 123                   Robert Asen                    Professor
    ## 124 Lydia Magdalena Tejeda Ashton          Assistant Professor
    ## 125               Randolph Ashton          Associate Professor
    ## 126                 Muhammad Asif                     Lecturer
    ## 127              Jennifer M Asmus                    Professor
    ## 128 Fariba Masoumeh Assadi-Porter               Assoc Lecturer
    ## 129                  Brad C Astor                    Professor
    ## 130                Julie Astrella           Clincal Assoc Prof
    ## 131               Sumudu Atapattu          Dis Admin Prgm Spec
    ## 132                    Alan David                    Professor
    ## 133                  Amaya Atucha          Assistant Professor
    ## 134                  Anjon Audhya                    Professor
    ## 135           Emily Kate Auerbach                    Professor
    ## 136                 Anthony Auger                    Professor
    ## 137           William Aughenbaugh              Professor (Chs)
    ## 138              Nicole Ann Aulik           Clinical Asst Prof
    ## 139                Htet Htet Aung               Assoc Lecturer
    ## 140                Karla Ausderau          Associate Professor
    ## 141                Joe Austerweil          Assistant Professor
    ## 142                  Gregory Avey        Assoc Professor (Chs)
    ## 143             Richard Avramenko                    Professor
    ## 144    Mouna Ayari Ben Hadj Kacem          Assoc Faculty Assoc
    ## 145                  Sharon W Ayd           Adjunct Assoc Prof
    ## 146       Samuel Alejandro Azocar              Senior Lecturer
    ## 147                  Jahana Azodi           Asst Faculty Assoc
    ## 148                 Jessica Babal         Asst Professor (Chs)
    ## 149                    Yash Babar          Assistant Professor
    ## 150                   Sue Babcock                    Professor
    ## 151                     Eric Bach                    Professor
    ## 152              Jonathan F. Bach          Clinical Assoc Prof
    ## 153              Taiya Renae Bach           Asst Faculty Assoc
    ## 154                Larissa E Back          Associate Professor
    ## 155              Hussain U. Bahia                    Professor
    ## 156                      Yang Bai          Associate Professor
    ## 157               Hannah E Bailey             Assistant Dean/M
    ## 158              Jesse Jonas Bair           Adjunct Instructor
    ## 159                     Ian Baird                    Professor
    ## 160                   Angie Baker          Clincial Instructor
    ## 161              Bernadette Baker                    Professor
    ## 162                   Tracy Baker          Associate Professor
    ## 163                     Karl Rohe          Associate Professor
    ##                            department                      degree_information
    ## 1             Obstetrics & Gynecology        PHD 1979 University of Edinburgh
    ## 2                      Anesthesiology            MD 2000 University of Assiut
    ## 3                                 Art           PHD 2012 Royal College of Art
    ## 4                            Pharmacy      PHD 2013 Univ of Wisconsin-Madison
    ## 5                  Information School       MA 2017 Univ of Wisconsin-Madison
    ## 6                          Psychology     PHD 1978 University of Pennsylvania
    ## 7                  Accting & Info Sys     MACC 2005 Univ of Wisconsin-Madison
    ## 8      Atmospheric & Oceanic Sciences      PHD 1987 Colorado State University
    ## 9              Mechanical Engineering  PHD 2008 Univ of Michigan at Ann Arbor
    ## 10     Atmospheric & Oceanic Sciences       PHD 2018 University of Washington
    ## 11                            Nursing      DNP 2017 Univ of Wisconsin-Madison
    ## 12                 Information School          MA University of South Florida
    ## 13          Animal And Dairy Sciences       PHD 2020 Univ of California Davis
    ## 14                         Psychology      PHD 1998 Univ of Wisconsin-Madison
    ## 15            School of Human Ecology                 PHD 2012 Ithaca College
    ## 16              Afro-American Studies      PHD 1989 Univ of Wisconsin-Madison
    ## 17                    Volunteer Staff            MD 1989 University of Aleppo
    ## 18         Curriculum And Instruction      PHD 2019 Univ of California Irvine
    ## 19        Engineering Research Center       MS 1997 Univ of Wisconsin-Madison
    ## 20           African Cultural Studies      PHD 2019 Univ of Wisconsin-Madison
    ## 21                    Plant Pathology      PHD 1981 Univ of Wisconsin-Madison
    ## 22                               <NA>             South Asian Sum Lang Instit
    ## 23                        Dermatology          PHD 1989 University of Lucknow
    ## 24               Neurological Surgery    MD 2003 Loyola University of Chicago
    ## 25         Asian Languages & Cultures          MA 2013 Ewha Womans University
    ## 26         Civil & Environmental Engr         PHD Univ of California Berkeley
    ## 27                                Art MFA 2007 Maryland Institute Colg of Art
    ## 28                           Medicine   MD 2002 U of California San Francisco
    ## 29                        Mathematics    PHD 2019 Univ of California Berkeley
    ## 30                         Law School            JD 1972 Marquette University
    ## 31                          Economics     PHD 2014 University of Pennsylvania
    ## 32     Engr Professional Develompment                                     PHD
    ## 33                  Computer Sciences     PHD 2005 Carnegie-Mellon University
    ## 34                            Surgery          PHD 2012 University of Alberta
    ## 35                         Pediatrics              MD 2005 Al-Quds University
    ## 36          Industrial & Systems Engr       PHD 2004 University of Pittsburgh
    ## 37                           Oncology    PHD 1992 Univ of California Berkeley
    ## 38      Community & Environ Sociology             PHD 2002 Cornell University
    ## 39                  Computer Sciences          PHD 2014 University of Toronto
    ## 40             Educational Psychology       PHD 2002 Arizona State University
    ## 41          Industrial & SYstmes Engr PHD 2006 Univ of IL at Urbana-Champaign
    ## 42                           Medicine           MD 1984 University of Vermont
    ## 43             Spanish and Portuguese     PHD 1994 Univ Complutenes de Madrid
    ## 44       Management & Human Resources      PHD 1974 Michigan State University
    ## 45                          Economics PHD 2009 Univ of California Los Angeles
    ## 46                   Medical Sciences                                    <NA>
    ## 47                    Medical Physics          PHD 1994 University of Arizona
    ## 48                            English   MA 2007 University of Central Florida
    ## 49                            Nursing      PHD 2018 Univ of Wisconsin-Madison
    ## 50                   Military Science                                 BA 2002
    ## 51        South Asian Sum Lang Instit                                     PHD
    ## 52                         Psychology          PHD 1994 University of Chicago
    ## 53               Neurological Surgery  PHD 2003 Univ of Michigan at Ann Arbor
    ## 54                    Plant Pathology  PHD 1987 VA Polytechnic Inst & State U
    ## 55                         Pediatrics                 MD 1980 Duke University
    ## 56                 French And Italian               PHD 2002 Emory University
    ## 57                Engineering Physics     PHD 2005 Georgia Inst of Technology
    ## 58                            English                PHD 2006 Duke University
    ## 59         Electrical & Computer Engr       MS 1983 Univ of Wisconsin-Madison
    ## 60           Gender And Women Studies      PHD 2002 Univ of Wisconsin-Madison
    ## 61        Mead Witter School Of Music    PHD 2002 Clevland Institute of Music
    ## 62                   Academic Affairs      PHD 2006 Univ of Wisconsin-Madison
    ## 63                          Marketing  PHD 1996 Pennsylvania State University
    ## 64      Engr Professional Development      PHD 2013 Univ of Wisconsin-Madison
    ## 65                   Medical Sciences      DVM 2003 Michigan State Universtiy
    ## 66             Spanish And Portuguese           PHD Univ of Wisconsin-Madison
    ## 67                       Bacteriology              PHD 2007 Baylor University
    ## 68                Integrative Biology      PHD 1999 Univ of Wisconsin-Madison
    ## 69                       Biochemistry             PHD 1982 Indiana University
    ## 70                                Art      PHD 2018 Univ of Wisconsin-Madison
    ## 71                            English             PHD 2011 Indiana University
    ## 72                 Information School      MS 2007 Georgia Inst of Technology
    ## 73                         Statistics                PHD 2019 Ohio University
    ## 74      Rehab Psychology & Special Ed           PHD 2018 University of Kansas
    ## 75                       Bacteriology  PHD 2014 Univ of Michigan at Ann Arbor
    ## 76             Spanish And Portuguese      PHD 2004 Univ of Wisconsin-Madison
    ## 77             German Nordic & Slavic         PHD 2015 University of Helsinki
    ## 78         Electrical & Computer Engr      PHD 1984 Univ of Wisconsin-Madison
    ## 79                        Mathematics                     PHD Duke University
    ## 80      Community & Environ Sociology      PHD 2019 Univ of Wisconsin-Madison
    ## 81                            Nursing      PHD 2006 Univ of Wisconsin-Madison
    ## 82             Mechanical Engineering      PHD 1998 Univ of Wisconsin-Madison
    ## 83               Nutritional Sciences       MS 1995 Univ of Wisconsin-Madison
    ## 84                     Administration  PHD 1982 Univ of Minnesota-Twin Cities
    ## 85                           Medicine PHD 1999 Univ of Dublin-Trinity College
    ## 86                           Medicine       MD 1992 Univ of Missouri-Columbia
    ## 87                        Kinesiology        PHD Univ of Alabma at Birmingham
    ## 88                          Geography PHD 2014 University of Texas At El Paso
    ## 89           PHD 2019 Duke University                                        
    ## 90                        Mathematics    PHD 2010 Univ of California Berkeley
    ## 91                        Art History         PHD 2001 University of Deleware
    ## 92                             Botany   PHD 2000 U de Toulouse II (Le Mirail)
    ## 93                       Bacteriology   PHD 2002 U de Toulouse II (Le Mirail)
    ## 94     Biological Systems Engineering       PHD 1995 Univ of California Davis
    ## 95                        Mathematics           PHD 1986 State Univ Of Leiden
    ## 96                   Medical Sciences   DVM 1999 Univ Ncnl Autonoma de Mexico
    ## 97            School of Human Ecology MFA 1991 Sch Of THE Art Inst Of Chicago
    ## 98                           Agronomy       MS 2020 Univ of Wisconsin-Madison
    ## 99                            Nursing   MSN 2007 Univ of Wisconsin-Eau Claire
    ## 100                     Asian Studies                                  M.PHIL
    ## 101              Nutritional Sciences       BS 2013 Univ of Wisconsin-Madison
    ## 102                      Biochemistry        PHD 1995 Northwestern University
    ## 103           Obstetrics & Gynecology         MD 2008 University Of Rochester
    ## 104    Engineering Student Developmnt     MS 1996 Univ of Wisconsin-Green Bay
    ## 105                           History            PHD 1971 Columbia University
    ## 106                        Law School                PHD 2017 Yale University
    ## 107     Real Estate & Urgan Land Econ                PHD Standford University
    ## 108           Comparative Biosciences      PHD 2002 Univ of Wisconsin-Madison
    ## 109                           English       MA 1972 Univ of Wisconsin-Madison
    ## 110                       Mathematics                  PHD Harvard University
    ## 111            Spanish And Portuguese          PHD 2011 Georgetown University
    ## 112                French And Italian         PHD 2013 University of Virginia
    ## 113                   Volunteer Staff       MD 2005 Univ of Wisconsin-Madison
    ## 114     Materials Science&Engineering        PHD 2006 Northwestern University
    ## 115                  Small Animal Iii      DPT 1994 Univ of Wisconsin-Madison
    ## 116                         Marketing          PHD 1995 Ohio State University
    ## 117                 Computer Sciences    PHD 1998 Univ of California Berkeley
    ## 118                Computer Sciencess    PHD 1998 Univ of California Berkeley
    ## 119                      Soil Science      PHD 2000 Univ of Wisconsin-Madison
    ## 120         Animal And Dairy Sciences       PHD 2013 VA Polytechnic & State U
    ## 121                               Art MFA 2000 Pennsylvania Acad of Fine Arts
    ## 122          Pathobiological Sciences                                PHD 2014
    ## 123                Communication Arts        PHD 1998 Northwestern University
    ## 124           School Of Human Ecology    PHD 2014 Univ of California Berkeley
    ## 125            Biomedical Engineering    PHD 2007 Rensselaer Polytechnic Inst
    ## 126        Asian Languages & Cultures            EDD 2015 University of Leeds
    ## 127            Educational Psychology             PHD 1995 University of Iowa
    ## 128               Integrative Biology      PHD 1994 Univ of Wisconsin-Madison
    ## 129                          Medicine       PHD 2000 Johns Hopkins University
    ## 130                           Nursing               MSN 2009 Edgewood College
    ## 131                        Law School        PHD 1995 University of Cambridge
    ## 132                      Biochemistry   PHD 1980 Univ of California San Diego
    ## 133                      Horticulture             PHD 2012 Cornell University
    ## 134            Biomolecular Chemistry   PHD 2002 Univ of California San Diego
    ## 135    Liberal Arts & Applied Studies       PHD 1981 University of Washington
    ## 136                        Psychology  PHD 1998 Univ of Massachusetts Amherst
    ## 137                       Dermatology    MD 1997 Medical College Of Wisconsin
    ## 138              Madison Microbiology      PHD 2010 Univ of Wisconsin-Madison
    ## 139                Information School      MS 2003 Carnegie-Mellon University
    ## 140                       Kinesiology    PHD 2009 Univ of Southern California
    ## 141                        Psychology    PHD 2012 Univ of California Berkeley
    ## 142                         Radiology        MD 2005 University of Washington
    ## 143                 Political Science          PHD 2004 Georgetown University
    ## 144                 Computer Sciences   PHD 2009 Uni Pierre&Marie Curie Paris
    ## 145                          Pharmacy         PHD Univ of Illinois at Chicago
    ## 146                           English      PHD 2011 Univ of Wisconsin-Madison
    ## 147 MFA 2014 University of Cincinnati                                        
    ## 148                        Pediatrics        MD 2012 University of Cincinnati
    ## 149     Operations & Information Mgmt  PHD 2020 Univ of Minnesota-Twin Cities
    ## 150     Materials Science&Engineering                                        
    ## 151                 Computer Sciences    PHD 1984 Univ of California Berkeley
    ## 152                  Medical Sciences      DVM 2000 Univ Of Minnesota-St Paul
    ## 153              Nutritional Sciences              MPH 2008 Tulane University
    ## 154    Atmospheric & Oceanic Sciences       PHD 2007 University of Washington
    ## 155        Civil & Environmental Engr  PHD 1991 Pennsylvania State University
    ## 156                           Physics                     PHD Yale University
    ## 157    Admin:Student Academic Affairs  MA 2013 Clg of William & Mary-Virginia
    ## 158                        Law School                                 JD 2013
    ## 159                         Geography PHD 2008 University of British Columbia
    ## 160                           Nursing       MS 2009 Univ of Wisconsin-Madison
    ## 161        Curriculum And Instruction      PHD 1997 Univ of Wisconsin-Madison
    ## 162           Comparative Biosciences      PHD 2001 Univ of Wisconsin-Madison
    ## 163                        Statistics    PHD 2011 Univ of California Berkeley
