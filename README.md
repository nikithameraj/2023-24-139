<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="webthemez">
    <title>SecureX</title>
	<!-- core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/font-awesome.min.css" rel="stylesheet">
    <link href="css/animate.min.css" rel="stylesheet"> 
    <link href="css/prettyPhoto.css" rel="stylesheet">
    <link href="css/styles.css" rel="stylesheet"> 
    <!--[if lt IE 9]>
    <script src="js/html5shiv.js"></script>
    <script src="js/respond.min.js"></script>
    <![endif]-->       
    <link rel="shortcut icon" href="images/ico/favicon.ico"> 
</head> 

<body id="home">
    <header id="header">
        <nav id="main-nav" class="navbar navbar-default navbar-fixed-top" role="banner">
            <div class="container">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="index.html"><img src="images/BLueWatCh-logos.png" alt="logo"></a>
                </div>
				
                <div class="collapse navbar-collapse navbar-right">
                    <ul class="nav navbar-nav">
                        <li class="scroll active"><a href="#home">Home</a></li>  
                        

<li class="nav-item dropdown">

              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">

                Project Scope

              </a>

              <div class="dropdown-menu" aria-labelledby="navbarDropdown">

                <a class="dropdown-item" href="#project-scope">Literature Survey</a>

                <a class="dropdown-item" href="#research_gap">Research Gap</a>

                <a class="dropdown-item" href="#research_problem">Research Problem & Solution</a>

                <a class="dropdown-item" href="#research_objectives">Research Objectives</a>

                <a class="dropdown-item" href="#methodology">Methodology</a>

                <a class="dropdown-item" href="#tech_used">Technologies</a>

              </div>

            </li>				
                        <li class="scroll"><a href="#milestones">Milestones</a></li>
                        

<li class="nav-item dropdown">

                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">

                  Downloads

                </a>

                <div class="dropdown-menu" aria-labelledby="navbarDropdown">

                  <a class="dropdown-item" href="#downloads">Documents</a>

                  <a class="dropdown-item" href="#presentations">Presentations</a>

                </div>

            </li>
                        <li class="scroll"><a href="#portfolio">Gallery</a></li>
                        <li class="scroll"><a href="#our-team">About Us</a></li>
						<li class="scroll"><a href="#achievements">Achievements</a></li>
                        <li class="scroll"><a href="#contact-us">Contact Us</a></li>                        
                    </ul>
                </div>
            </div><!--/.container-->
        </nav><!--/nav-->
    </header><!--/header-->

    <section id="hero-banner">
             <div class="banner-inner">
                    <div class="container">
                        <div class="row">
                            <div class="col-sm-12">
                                 
                                    <center><h2>SecureX</h2></center>
                                    <h2 style="text-align: center;">SecureX</h2>
                                    <p>Network Infrastructure Management Tool <br/>with python and Machine Learning </p>
                                    <a class="btn btn-primary btn-lg" href="#project-scope">Learn More</a>
                                
                            </div>
                        </div>
                    </div>
                </div>
    </section><!--/#main-slider-->

 <section id="services" >
        <div class="container">

            <div class="section-header">
                <h2 class="section-title wow fadeInDown">Project Scope</h2>
                <p class="wow fadeInDown">This is the component of project implementation that helps determine goals, constraints, workflow management strategies, tasks, and deliverables.</p>
            </div>

            <section id="project-scope" class="main-sections" style="background-color:#FDFEFE">
                <div class="container">
                    
                    <!-- Literature Survey -->
                    <div id="literature" class="sub-section">
                        <h2>Literature Survey</h2>
                        <div class="row">
                          <div id="project-scope-left" class="col-md-6 col-sm-12 pt-lg-5">
                            <div class="section-left">
                              <div class="section-info-div">
                                
                              </div>
                              <!-- <div class="section-figure " > -->
                                <!-- <img style="align-items:center" src="./images/savewater.PNG" width="80%"/> -->
                                <br><br><br><br>
                                <img style="align-items:center" src="./images/water.png" width="80%" height="20%"/>
                              <!-- </div> -->
                            </div>
                          </div>
                          <div id="project-scope-right" class="col-md-6 col-sm-12 pt-lg-5 justify-text">
                          <br>
                          <br>  
                            
                           <p>SecureX is a sophisticated product that integrates advanced network management and security features using Python scripts and machine learning (ML) techniques. This literature survey examines the core functionalities of SecureX, including bulk configuration tools, network self-healing, DDoS attack detection, and brute force attack detection, highlighting the relevant research and practical guides that underpin these features.

                                 Bulk Configuration Tool Using Python Scripts

                                SecureX enhances network administration by incorporating Python scripts for bulk configuration, enabling efficient management of network devices. Literature such as "Network Automation Using Python" provides comprehensive guidance on using Python for network automation, focusing on essential libraries like Netmiko and NAPALM, which are crucial for developing bulk configuration tools. Additionally, the "Python Network Programming Cookbook" offers practical examples of network programming with Python, including scripts for bulk configuration and device management. Furthermore, "Automate the Boring Stuff with Python" contains insights into automating repetitive tasks using Python, which is directly applicable to network configurations in SecureX.

                                Network Self-Healing Using Python Scripts

                                SecureX includes network self-healing capabilities, allowing the network to autonomously detect and resolve issues using Python scripts. The paper "Self-Healing Networks: A Survey" reviews various self-healing techniques, including Python-based automation and scripting. "Python for Network Engineers" provides practical examples of Python scripts for creating self-healing mechanisms in network environments, covering aspects such as monitoring, fault detection, and automatic recovery. Moreover, "Network Programmability and Automation" explores automating networks with Python, including developing scripts for self-healing and discussing event-driven scripting and network monitoring tools like SNMP and NetFlow, which are integral to SecureX’s self-healing functionality.

                                DDoS Attack Detection Using Machine Learning

                                SecureX employs machine learning models to detect Distributed Denial of Service (DDoS) attacks by analyzing network traffic patterns and distinguishing between normal and malicious activities. The survey paper "A Survey on DDoS Attack Detection and Prevention Using Machine Learning Techniques" offers an extensive review of ML techniques for DDoS detection, covering both supervised and unsupervised learning methods. The "Machine Learning for Cybersecurity Cookbook" includes practical examples and code snippets for using ML to detect cyber threats, including DDoS attacks, with a focus on Python libraries like scikit-learn and TensorFlow. Additionally, "Applied Machine Learning for Network Security" covers the application of ML in network security, with chapters dedicated to detecting DDoS attacks using various ML algorithms, directly supporting the capabilities of SecureX.

                                 Brute Force Attack Detection Using Machine Learning

                                SecureX integrates ML models to detect brute force attacks by analyzing login attempts and identifying abnormal patterns. The research article "Detection of Brute Force Attacks in Cloud Environments Using Machine Learning" explores ML-based approaches for detecting brute force attacks in cloud environments, highlighting feature selection and model accuracy. "Machine Learning and Security: Protecting Systems with Data and Algorithms" discusses the use of ML for security purposes, including methods for detecting brute force attacks, and provides Python code examples for building and training detection models. Furthermore, "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" offers foundational knowledge on applying ML in various contexts, including security, with practical projects related to anomaly detection that can be adapted for brute force attack detection in SecureX.</p>
                            <div class="references">
                                <br>
                              <p class="pt-sm-1"><strong>References</strong></p>
                              <ol>
                                <li>[1] R. A. R. M. K. a. A. R. M. A. M. Mazin, 
                                        "Performance analysis on network automation 
                                        interaction with network devices using python," IEEE 
                                        11th Symposium on Computer Applications Industrial 
                                        Electronics (ISCAIE), 2021.
                                <li> [2] L. Z. e. al, " "Autonomous Network Repair: 
                                        Framework for Self-Healing Networks"," IEEE 
                                        Transactions on Network and Service Management, 
                                        vol. 5, no. 3, 2009. 
                                <li>[3]J. Raj and D. O. Wu, ""DDoS Attacks: Evolution, 
                                        Detection, Prevention, Reaction, and Tolerance"," 
                                        IEEE Communications Surveys & Tutorials, vol. 18, 
                                        no. 1, pp. 399-465, 2016. 
                              </ol>
                            </div>
                          </div>
                        </div>
                    </div>
                    <!-- Research Gap -->
                    <div id="research_gap" class="sub-section" >
                      <h2>Research Gap</h2>
                      
                      <div class="row mt-5 research-gap">
                    <div class="container">
                    <div class="row">
                        <div class="col-md-4">
                            <div class="fa-container text-center">
                                
                            </div>
                            
                            
                            </div>
                            <div>
                                <p> generated configuration files were deployed to therespective devices using SSH protocol, and the deployment process was monitored in real-time.Accurately configure the efficiency of automated responses, including configuration changes, service restarts, and failover mechanisms.check your network traffic file for bruteforce attack using three algorithms and get your result separately.an intuitive user-friendly interface has been developed to facilitate real-time detection of DDoS attacks.</p>
                            </div>
                        </div>
                        
            
        
                    </div>
                    </div> 
                      </div>
                  </div>
                    <!-- Research Problem -->
                    <div id="research_problem" class="sub-section">
                      <h2>Research Problem & Solution</h2>
                       <div class="row">
                        <div id="project-scope-left" class= "justify-text">
                         <h5 style="color: #F9690E"><strong>Proposed Problem</strong></h5>
                         </br>
                           
                            <p></p>
                            <p>In the modern network environment, ensuring security, efficiency, and reliability is paramount. However, existing solutions for network management and security, such as Cisco Prime Infrastructure, Ansible, and SolarWinds NCM, often come with significant costs and inflexibility. Additionally, traditional methods for network troubleshooting and cyber threat detection struggle with efficiency and accuracy. There is a critical need for scalable, cost-effective, and secure solutions that leverage open-source technologies to address these challenges. This research project aims to develop and implement a comprehensive suite of tools within the SecureX framework to enhance network security, efficiency, and reliability.</p>
                        </br>
                        </div>
        
                       
                        </div>
                      </div>


<!-- Research Problem -->
                    <div id="research_problem" class="sub-section">
                      <h2>Research Problem & Solution</h2>
                       <div class="row">
                        <div id="project-scope-left" class= "justify-text">
                         <h5 style="color: #F9690E"><strong>Proposed Solution</strong></h5>
                         </br>
                           
                            <p></p>
                            <p>Our research project is centered around developing comprehensive solutions to enhance network 
                            security, efficiency, and reliability through innovative technologies. We start by addressing the 
                            challenge of bulk configuration in Cisco routers, aiming to replace costly and inflexible solutions 
                            like Cisco Prime Infrastructure, Ansible, and SolarWinds NCM with a scalable and secure Pythonbased tool. This solution not only optimizes efficiency and error handling but also ensures secure 
                            credential management and customization options, offering a cost-effective alternative leveraging 
                            open-source libraries.we focus on automating network troubleshooting using Netmiko to swiftly detect 
                            and resolve configuration issues.we explore the application of Machine Learning to combat brute force attacks in network environments. Current detection methods often struggle with accuracy, prompting us to develop 
                            models that accurately detect attack patterns in network traffic. Our system integrates adaptive 
                            blocking mechanisms to minimize disruptions from suspicious IPs while promptly alerting 
                            administrators through syslogs or notifications. This approach is underpinned by rigorous literature 
                            review, model development using historical data, and comprehensive evaluation to ensure 
                            robustness and effectiveness.</p>
                        </br>
                        </div>
        
                       
                        </div>
                      </div>







                         
                    <!-- Research Objectives -->
               <div id="research_objectives" class="sub-section">
                      <h2>Research Objectives</h2>
                       <div class="row">
                        <div id="project-scope-left" class= "justify-text">
                         
                         </br>
                           
                            <p></p>
                            <p style="color: #877e78; text-align: justify; font-family: 'Raleway', sans-serif; font-style: none; font-size: 14px">The first objective is automate and streamline the process of configuring multiple Cisco routers within a network infrastructure. The primary goal is to achieve increased operational efficiency, consistency, and reliability in network configurations.</p>

                        </br>
                        </div>
						<hr class="decorative-line">

						 <div id="project-scope-left" class= "justify-text">
                         
                        </strong></h5>
                         </br>
                           
                            <p></p>
                            <p style="color: #877e78; text-align: justify; font-family: 'Raleway', sans-serif; font-style: none; font-size: 14px">The second objective of this study aimed to enhancing network reliability and security by enabling real-time failure detecting, and the execution of immediate corrective actions without human intervention.</p>
                        </br>
                        </div>
						<hr class="decorative-line">

						 <div id="project-scope-left" class= "justify-text">
                        
                         </br>
                           
                            <p></p>
                            <p style="color: #877e78; text-align: justify; font-family: 'Raleway', sans-serif; font-style: none; font-size: 14px">The third objective is capture network traffic & develop a user-friendly interface for uploading network packet files and implementing machine learning models for bruteforce attack detection.</p>
                            </p>
                        </br>
                        </div>
						<hr class="decorative-line">

						 <div id="project-scope-left" class= "justify-text">
                         
                         </br>
                           
                            <p></p>
                            <p style="color: #877e78; text-align: justify; font-family: 'Raleway', sans-serif; font-style: none; font-size: 14px">The fourth objective is accurately identify and detect DOS & DDOS attacks using machine learning & packet analyzing and visualization.</p>
                        </br>
                        </div>
        
                       
                        </div>
                      </div>
                    <!-- Methodology -->
                    <div id="methodology" class="sub-section">
                      <h2>Methodology</h2>
                      <div class="row">
                        <div id="project-scope-left" class="col-md-6 col-sm-12 pt-lg-5">
                          <div class="section-left">
						  <br>
                            <!-- <div class="section-figure"> -->
                              <br><br><br><br><br><br><br>
                              <img src="./images/all update.drawio.png" width="100%"/>
                              <p style="color: #000000">Figure: High Level Architecture of the system.</p>
                            <!-- </div> -->
                          </div>
                        </div>
                        <div id="project-scope-right" class="col-md-6 col-sm-12 pt-lg-5 justify-text">
                          <p>The proposed Network Infrastructure  consists of 4 main components. They are;</p>
                          <ol>
                            <li><strong>Bulk Configuration for Cisco Routers</strong></li>
                            <li><strong>Network Self-Healing</strong></li>
                            <li><strong>Machine Learning Driven Brute-Force Attack 
                                        Detection System with Adaptive Blocking and Alert 
                                        Triggers</strong></li>
                            <li><strong>DDOS Attack Detection Using Machine Learning</strong></li>
                            
                          </ol>
                          <p> The implementation of SecureX involves a systematic approach to integrating bulk configuration tools, network self-healing mechanisms, and security features for detecting DDoS and brute force attacks using Python scripts and machine learning techniques. The process begins with requirements analysis, where stakeholder interviews and feature specifications are conducted to understand the needs and technical requirements. The system architecture is then designed, detailing the components for bulk configuration, self-healing, and attack detection, along with integration points with existing systems and the technology stack, including Python libraries and network monitoring tools. Development follows, where Python scripts for bulk configuration are created using Netmiko and NAPALM, self-healing mechanisms are developed for continuous monitoring and automated responses, and ML models are trained for DDoS and brute force attack detection using collected network traffic data. These components undergo unit, integration, performance, and security testing to ensure functionality and effectiveness. Deployment involves setting up SecureX in a staging environment, using configuration management tools for automation, and providing comprehensive documentation. Post-deployment, continuous monitoring and regular updates are essential for maintaining optimal performance and security, supported by a feedback loop with stakeholders for continuous improvement. Training programs for network administrators and security analysts, along with ongoing technical support, ensure effective usage and management of SecureX, resulting in a robust, efficient, and secure network environment capable of addressing modern challenges.</p>

                          <!-- <p>Once the system identifies that the leaves are infected, then the response will be captured by the crowdsourcing platform. The Google Map will be updated with the real time locations (latitude and longitude) of the infected palms. In Addition, the system will automatically send notifications to the farmers and other stakeholders who are at the risk of infection.</p> -->
                        </div>
                      </div>
                  </div>
                    </div><!--/.col-md-4-->
                </div>
            </div><!--/.row-->    
        </div><!--/.container-->
    </section><!--/#services-->
	
	   <section id="tech_used">
       <!-- Technologies Used -->
<div id="tech_used" class="sub-section">
    <h2>Technologies and Tools Used</h2>
    <div class="row technology mt-5">
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/python.png" alt="Python">
    </div>
    <p>Python</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/react.png" alt="React">
    </div>
    <p>React</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/tensorflow.png" alt="Python">
    </div>
    <p>Tensorflow</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/keras.png" alt="Keras">
    </div>
    <p>Keras</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/googlecolab.png" alt="MongoDB">
    </div>
    <p>Google Colab</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/googlecloud.png" alt="Google Cloud">
    </div>
    <p>Google Cloud</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/vscode.png" alt="Kafka">
    </div>
    <p>VS Code</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/flask.png" alt="Doker">
    </div>
    <p>Flask</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/git lab.png" alt="Google Colab">
    </div>
    <p>Git Lab</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/statmodels.png" alt="Google map API">
    </div>
    <p>Stat Models</p>
    </div>
    <div class="col-md-2 col-sm-4 col-6 mb-5">
    <div class="avatar">
    <img src="images/numpy.png" alt="Jwt">
    </div>
    <p>Numpy</p>
    </div>
    </div>
    </div>
    </section><!--/#our-team-->

    <!-- Milestones -->
    <section id="milestones" class="sub-section" >
        <div class="container">
            <div class="section-header">
                <h2 class="section-title wow fadeInDown">Milestones</h2>
                
            </div>
            <div class="sub-section">
                <h2>Timeline in Brief</h2>
                <div class="milestones">
                  <ul class="timeline">
                    <!-- Project Proposal -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">July 2023</p>
                        <h3>Project Proposal</h3>
                        <p>A Project Proposal is presented to potential sponsors or clients to receive funding or get your project approved.</p>
                        <p><strong>Marks Allocated : </strong>12</p>
                        <div class="progress">
                          <div class="progress-bar bg-success" role="progressbar" style="width: 12%" aria-valuenow="12" aria-valuemin="0" aria-valuemax="100">12%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Progress Presentation I -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">November 2023</p>
                        <h3>Progress Presentation I</h3>
                        <p>Progress Presentation I reviews the 50% completetion status of the project. This reveals any gaps or inconsistencies in the design/requirements.</p>
                        <p><strong>Marks Allocated : </strong>15</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 27%" aria-valuenow="13" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 27%" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100">27%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Research Paper -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">July 2024</p>
                        <h3>Research Paper</h3>
                        <p>Describes what you contribute to existing knowledge, giving due recognition to all work that you referred in making new knowledge</p>
                        <p><strong>Marks Allocated : </strong>10</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 37%" aria-valuenow="27" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 37%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100">37%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Progress Presentation II -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">July 2024</p>
                        <h3>Progress Presentation II</h3>
                        <p>Progress Presentation II reviews the 90% completetion status demonstration of the project. Along with a Poster presesntation which describes the project as a whole.</p>
                        <p><strong>Marks Allocated : </strong>18</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 55%" aria-valuenow="37" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 55%" aria-valuenow="18" aria-valuemin="0" aria-valuemax="100">55%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Website -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">June 2024</p>
                        <h3>Website Assessment</h3>
                        <p>The Website helps to promote our research project and reveals all details related to the project.</p>
                        <p><strong>Marks Allocated : </strong>2</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 57%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 57%" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100">57%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Logbook -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">July 2024</p>
                        <h3>Logbook and Progress Reports</h3>
                        <p>Status of the project is validated through the Logbook. This also includes, Status documents 1 & 2.</p>
                        <p><strong>Marks Allocated : </strong>4</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 61%" aria-valuenow="57" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 61%" aria-valuenow="4" aria-valuemin="0" aria-valuemax="100">61%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Final Report -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">May 2024</p>
                        <h3>Final Report</h3>
                        <p>Final Report evalutes the completed project done throughout the year. Marks mentioned below includes marks for Individual & group reports and also Final report.</p>
                        <p><strong>Marks Allocated : </strong>19</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 80%" aria-valuenow="61" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 80%" aria-valuenow="29" aria-valuemin="0" aria-valuemax="100">80%</div>
                        </div>
                      </div>
                    </li>
                    <!-- Viva -->
                    <li class="timeline-event">
                      <label class="timeline-event-icon"></label>
                      <div class="timeline-event-copy">
                        <p class="timeline-event-thumbnail">May 2024</p>
                        <h3>Final Presentation & Viva</h3>
                        <p>Viva is held individually to assess each members contribution to the project.</p>
                        <p><strong>Marks Allocated : </strong>20</p>
                        <div class="progress">
                          <!-- <div class="progress-bar bg-infinity-primary" role="progressbar" style="width: 100%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div> -->
                          <div class="progress-bar bg-success" role="progressbar" style="width: 100%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100">100%</div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
            </div>
        </div>
      </section>
	  
	  
	  
	  <!-- Downloads -->
      <section id="downloads" class="main-sections" >
        <div class="container">
            <h5 class="section-headings">Downloads</h5>
            <!-- Documents -->
            <div class="sub-section">
                <h2>Documents</h2>
                <p>Please find all documents related to this project below.</p>


                                  <!-- Final Report -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Status Docs</h5>
                        <p class="card-text pt-sm-2">It20631338</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Status Doc 1 &nbsp;&nbsp;<a href="https://drive.google.com/file/d/1XbTD6TE5DDd8WJrfQCh6jfGfWo9e7OTB/view?usp=sharing" target="_blank">Download</a></li>
                        <li class="list-group-item">Status Doc 2&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1o9mKgdGM9MAEd_5_OfaSjT0FlT4eB6Nm/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>

                    </div>
                  </div>



                                  <!-- Final Report -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Status Docs</h5>
                        <p class="card-text pt-sm-2">It20301668</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Status Doc 1 &nbsp;&nbsp;<a href="https://docs.google.com/document/d/1PXUaXCQt4BIPbb9-GwCUvViuVu2a6B6P/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                        <li class="list-group-item">Status Doc 2&nbsp;&nbsp;<a href="https://docs.google.com/document/d/1PXUaXCQt4BIPbb9-GwCUvViuVu2a6B6P/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>


                                    <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Status Docs</h5>
                        <p class="card-text pt-sm-2">It20627928</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Status Doc 1 &nbsp;&nbsp;<a href="https://drive.google.com/file/d/1vdkE6-mqBFKfHCdTKy-k9wIkYsUtonhS/view?usp=sharing" target="_blank">Download</a></li>
                        <li class="list-group-item">Status Doc 2&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1jeHBMTYoUn6mXJutB77v3OnUr2gnSyvZ/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>



                                      <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Status Docs</h5>
                        <p class="card-text pt-sm-2">It20623036</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Status Doc 1 &nbsp;&nbsp;<a href="https://drive.google.com/file/d/1o9mKgdGM9MAEd_5_OfaSjT0FlT4eB6Nm/view?usp=sharing" target="_blank">Download</a></li>
                        <li class="list-group-item">Status Doc 2&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1o9mKgdGM9MAEd_5_OfaSjT0FlT4eB6Nm/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>




                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Research Paper</h5>
                        <p class="card-text pt-sm-2">Submitted on 2024/03/04</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1ki5wUR8soabJJIumBkenpeGSBkcc0VgM/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>

                    </div>
                  </div>

                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Final Report</h5>
                        <p class="card-text pt-sm-2">Submitted on 2024/04/05</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">It20627928 &nbsp;&nbsp;<a href="https://drive.google.com/file/d/1ZpmxfVvxZY0Sf5b-d1iwmX5pXWS40Dc-/view?usp=sharing" target="_blank">Download</a></li>
                        <li class="list-group-item">It20623036&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1ZpmxfVvxZY0Sf5b-d1iwmX5pXWS40Dc-/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>

                    </div>
                  </div>


                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-pdf mr-2 download-pdf"></i>Final Report</h5>
                        <p class="card-text pt-sm-2">Submitted on 2024/04/05</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">It20631338 &nbsp;&nbsp;<a href="https://drive.google.com/file/d/1ZpmxfVvxZY0Sf5b-d1iwmX5pXWS40Dc-/view?usp=sharing" target="_blank">Download</a></li>
                        <li class="list-group-item">It20301668&nbsp;&nbsp;<a href="https://drive.google.com/file/d/1ZpmxfVvxZY0Sf5b-d1iwmX5pXWS40Dc-/view?usp=sharing" target="_blank">Download</a></li>
                      </ul>

                    </div>
                  </div>


                  
                </div>
            </div>
            <!-- Presentations -->
            <div id="presentations" class="sub-section">
                <h2>Presentations</h2>
                <p>Please find all presentations related this project below.</p>
                <div class="row mt-sm-5 downloads-container">
                  <!-- Project Proposal -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-powerpoint mr-2 download-powerpoint"></i></i>Project Proposal</h5>
                        <p class="card-text pt-sm-2">Submitted on 2023/03/27</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Group &nbsp;<a href="https://docs.google.com/presentation/d/1lRogfCdGfI44H_P1JQuYkeKwQlgeD8hn/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>
                  <!-- Progress Presentation I -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-powerpoint mr-2 download-powerpoint"></i></i>Progress Presentation I</h5>
                        <p class="card-text pt-sm-2">Submitted on 2023/05/22</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Group &nbsp;<a href="https://docs.google.com/presentation/d/1lRogfCdGfI44H_P1JQuYkeKwQlgeD8hn/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>
                  <!-- Progress Presentation II -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-powerpoint mr-2 download-powerpoint"></i></i>Progress Presentation II</h5>
                        <p class="card-text pt-sm-2">Submitted on 2023/09/04</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Group &nbsp;<a href="https://docs.google.com/presentation/d/1lRogfCdGfI44H_P1JQuYkeKwQlgeD8hn/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>
                  <!-- Final Presentation -->
                  <div class="col-lg-3 col-md-4 col-sm-12">
                    <div class="card" >
                      <div class="card-body">
                        <h5 class="card-title"><i class="fas fa-file-powerpoint mr-2 download-powerpoint"></i></i>Final Presentation</h5>
                        <p class="card-text pt-sm-2">Submitted on 2023/10/31</p>
                      </div>
                      <ul class="download-items list-group list-group-flush">
                        <li class="list-group-item">Group &nbsp;<a href="https://docs.google.com/presentation/d/1lRogfCdGfI44H_P1JQuYkeKwQlgeD8hn/edit?usp=sharing&ouid=101317423239018164131&rtpof=true&sd=true" target="_blank">Download</a></li>
                      </ul>
                    </div>
                  </div>
                </div>
            </div>
        </div>
      </section>

  


  

  <section id="portfolio">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title wow fadeInDown">Gallery</h2>
                <p class="wow fadeInDown">Network Infrastructure Management Tool.</p>
            </div>

            <div class="text-center">
                <ul class="portfolio-filter" style="display:none">
                    <li><a class="active" href="#" data-filter="*">All Works</a></li>
                    <li><a href="#" data-filter=".designing">Designing</a></li>
                    <li><a href="#" data-filter=".mobile">Mobile App</a></li>
                    <li><a href="#" data-filter=".development">Development</a></li>
                </ul><!--/#portfolio-filter-->
            </div>

            <div class="portfolio-items">
                <div class="portfolio-item designing">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/05.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/01.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item mobile development">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/02.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/02.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item designing">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/07.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/03.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item mobile">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/08.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/04.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item designing development">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/03.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/05.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item mobile">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/04.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/06.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item designing development">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/06.jpg" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/07.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->

                <div class="portfolio-item mobile">
                    <div class="portfolio-item-inner">
                        <img class="img-responsive" src="images/portfolio/01.png" alt="">
                        <div class="portfolio-info"> 
                            <a class="preview" href="images/portfolio/08.jpg" rel="prettyPhoto"><i class="fa fa-eye"></i></a>
                        </div>
                    </div>
                </div><!--/.portfolio-item-->
            </div>
        </div><!--/.container-->
    </section><!--/#portfolio-->


   	<section id="our-team">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title wow fadeInDown">
OUR TEAM MEMBERS
</h2>

            </div>
			
			 	
            <div class="row text-center">
                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="0ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/01.jpg" alt="">
                        </div>
                        <div class="team-info">
                            <h3>Dharmapriya N.M </h3>
							<span>IT20631338​</span> 
                            <span> (Leader)</span> 
                        </div> 
                       
                    </div>
                </div>
                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="100ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/02.jpg" alt="">
                        </div>
                        <div class="team-info">
                            <h3>S N Denakumbura​</h3>
                            <span>IT20301668​</span> 
                        </div> 
                       
                    </div>
                </div>
                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="200ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/03.jpg" alt="">
                        </div>
                        <div class="team-info">
                            <h3>H M T D Herath</h3>
                            <span>IT20627928​</span> 
                        </div> 
                       
                    </div>
                </div>
                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="300ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/04.jpg" alt="">
                        </div>
                        <div class="team-info">
                            <h3>Jayashan H.S.P.C</h3>
                            <span>IT20623036</span> 
                        </div> 
                        
                    </div>
                </div>
            </div>

        </div>
    </section><!--/#our-team-->


<section id="our-team">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title wow fadeInDown">
SUPERVISOR AND CO-SUPERVISOR
</h2>


            
                
            <div class="row text-center">
                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="0ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/Hansika Mahaadikara 1.jpg" alt="">
                        </div>
                        <div class="team-info">
                            <h3>Hansika Mahaadikara</h3>
                            <span>Supervisor</span> 
                            
                        </div> 
                       
                    </div>
                </div>

                <div class="col-md-3 col-sm-6 col-xs-12">
                    <div class="team-member wow fadeInUp" data-wow-duration="400ms" data-wow-delay="300ms">
                        <div class="team-img">
                            <img class="img-responsive" src="images/team/Hansika Mahaadikara21.png" alt="">
                        </div>
                        <div class="team-info">
                            <h3>Shashika Lokuliyana</h3>
                            <span>Co-Supervisor</span> 
                        </div> 
                        
                    </div>
                </div>
            </div>

        </div>
    </section>

   <!-- Achievements -->
	   <section id="achievements" class="main-sections" >
        <div class="container">
        <div class="section-header">
                <h2 class="section-title wow fadeInDown">
Achievements
</h2>

            </div>
                  <div class="section-center">
                    <div class="section-figure text-center">
                      <img style="width: 70%; height: 200px" src="./images/icac.png">
                    </div>
                  </div>
				  <div>
				 </br>
				 <p style="text-align: justify;"> We are excited to announce that we have submitted our research paper for consideration at the prestigious 'WorldS4 UK 2024' (World Conference on Smart Trends in Systems, Security and Sustainability). Our paper explores cutting-edge developments and insights in the field of computing and aligns with the conference's mission to advance the frontiers of knowledge. We eagerly anticipate the opportunity to present our research at WorldS4 UK 2024, where we can engage with leading experts and contribute to the vibrant exchange of ideas in the world of computing.</P>
                </div>
        </div>
      </section>
   

  
   
    <section id="contact-us">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title wow fadeInDown">Contact Us</h2>
                <p class="wow fadeInDown">Get In Touch With Us <br> We Are Here to Provide The Best Service For You</p>
            </div>
        </div>
    </section><!--/#contact-us-->


    <section id="contact">
        
        <div class="container">
            <div class="container contact-info">
                <div class="row">
				  <div class="col-sm-4 col-md-4">
                        <div class="contact-form">
                            <h3>Contact Info</h3>


                                
                              
                            </address>
					</div></div>
                    <div class="col-sm-8 col-md-8">
                        <div class="contact-form">
                       
                            <form id="main-contact-form" name="contact-form" method="post" action="#">
                                <div class="form-group">
                                    <input type="text" name="name" class="form-control" placeholder="Name" required>
                                </div>
                                <div class="form-group">
                                    <input type="email" name="email" class="form-control" placeholder="Email" required>
                                </div>
                                <div class="form-group">
                                    <input type="text" name="subject" class="form-control" placeholder="Subject" required>
                                </div>
                                <div class="form-group">
                                    <textarea name="message" class="form-control" rows="8" placeholder="Message" required></textarea>
                                </div>
                                <button type="submit" class="btn btn-primary">Send Message</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>   
   </section><!--/#bottom-->

    <footer id="footer">
        <div class="container">
            <div class="row">
                <div class="col-sm-6">
                    &copy; 2023 SECUREX 
                </div>
                <div class="col-sm-6">
                    <ul class="social-icons">
                        <li><a href="#"><i class="fa fa-facebook"></i></a></li>
                        <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
                        <li><a href="#"><i class="fa fa-linkedin"></i></a></li> 
                        <li><a href="#"><i class="fa fa-youtube"></i></a></li>
                        <li><a href="#"><i class="fa fa-github"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer><!--/#footer-->

    <script src="js/jquery.js"></script>
    <script src="js/bootstrap.min.js"></script> 
    <script src="js/mousescroll.js"></script>
    <script src="js/smoothscroll.js"></script>
    <script src="js/jquery.prettyPhoto.js"></script>
    <script src="js/jquery.isotope.min.js"></script>
    <script src="js/jquery.inview.min.js"></script>
    <script src="js/wow.min.js"></script>
    <script src="js/custom-scripts.js"></script>
</body>
</html>
