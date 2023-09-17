<div class="main">
    <h1>SQL Server 2019 Installation Guide [Developer&nbsp;Edition]</h1>
    <article class="blogpost full">
      <div class="blogpost-content smooth-scroll">
        <p class="lead">This guide will help  Visual Expert  users to install SQL Server 2019 Developer edition.</p>
        <p><strong>Note: SQL Server is necessary to create the VE Repository and store code analysis data.</strong></p>
        <p><strong><a href="https://go.microsoft.com/fwlink/?linkid=866662" target="_blank">&gt;&gt; Download SQL Server 2019 Developer Edition</a></strong><a href="https://go.microsoft.com/fwlink/?linkid=866662"> </a></p>      
      <p>Once you have downloaded the .exe file, follow these steps to install and create an instance of SQL Server : </p>
      <ol>
      <li>Run the .exe file and choose <strong>"Download Media"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/run-sql-server-exe-file.png" alt="Run SQL Server Exe File"></li><br>
      <li>Select your <strong>Language</strong>, choose the <strong>‘ISO’</strong> package and your preferred <strong>Download Location</strong>. Then, click on <strong>‘Download’</strong>.
        <br>
        <br>
        <img src="https://www.visual-expert.com/images/choose-iso-package.png" alt="Choose ISO Package, language &amp; download location"></li><br>
      <li>The downloading process for the ISO package file begins.
        <br>
        <br>
        <img src="https://www.visual-expert.com/images/downloading-iso-package.png" alt="Downloading ISO Package Begins"></li><br>
      <li>On successful download, click on <strong>‘Open Folder’</strong> to locate the ISO file.
        <br>
        <br>
        <img src="https://www.visual-expert.com/images/locate-iso-file.png" alt="Locate the ISO File"></li><br>
      <li>Right click on the ISO file and click on <strong>‘Mount’</strong> to access the package files.
        <br>
        <br>
        <img src="https://www.visual-expert.com/images/access-iso-package-files.png" alt="Access ISO Package Files"></li><br>
      <li>Locate the installation package and setup file. <br><br>
        <img src="https://www.visual-expert.com/images/locate-sql-server-setup-file.png" alt="Locate the SQL Server 2019 Setup File"><br>
      </li>
      <br>
      <li>Right click on the setup file, and select <strong>"Run As Administrator"</strong>.<br><br> 
      <img src="https://www.visual-expert.com/images/run-as-administrator.png" alt="Run Setup File as Administrator"></li>
      <br>
      <li>The SQL Server Installation Center opens.<br>
      Select the first option:<br>
      <strong>"New SQL Server stand-alone installation or add features to an existing installation"</strong><br><br> 
      <img src="https://www.visual-expert.com/images/new-sql-server-installation.png" alt="New SQL Server Stand-alone Installation"></li>
      <br>
      <li> In the "Product Key" section, choose the <strong>"Developer"</strong> edition and click on <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/developer-edition-product-key.png" alt="Developer Edition Product Key"></li>
      <br>
      <li>Accept the license terms and click on <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/accept-license-terms.png" alt="Accept the license and terms"></li>
      <br>
         <li>Make sure all <strong>"Global Rules"</strong> pass the  test and click <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/global-rules-scan-test.png" alt="Global Rules Scanning Test"></li>
      <br>
      <li>In the <strong>"Microsoft Update"</strong> window, enable <strong>"Check for Updates"</strong> to allow the installer to automatically check for possible software updates. <br>
  Click on <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/check-for-microsoft-updates.png" alt="Check for Microsoft Updates"></li>
      <br>
      <li>The setup files will get installed in the next window - <strong>Install Setup Files</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/install-setup-files.png" alt="Install Setup Files"></li>
      <br>
       <li>The "<strong>Feature Selection</strong>" window allows you to select which SQL Server components will be installed.<br>
         <br>
      <img src="https://www.visual-expert.com/images/install-selected-components-of-sql-server.png" alt="Install Selected Components of SQL Server"></li>
      <br>
      <li>Select the "<strong>Instance features</strong>" as shown below, as they are mandatory for SQL Server to work with Visual Expert. Then, click "Next".<br>
        <br>
      <img src="https://www.visual-expert.com/images/mandatory-instance-features-for-visual-expert.png" alt="Mandatory Instance Features for Visual Expert"><br></li><br>
      <li>In the <strong>"Instance Configuration"</strong> window, create a "<strong>VE_Server</strong>" Named instance  and click <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/create-named-instance.png" alt="Name Instance Configuration"><br></li><br>
      <li>The <strong>"Server Configuration"</strong> window allows users to configure Service Accounts. <br>
        Click <strong>"Next"</strong> if no change is required in the default account settings.<br>
        <br>
      <img src="https://www.visual-expert.com/images/server-configuration-window.png" alt="Server Configuration Window"><br></li><br>
       <li>In the <strong>Database Engine Configuration</strong> window, under the <strong>Server Configuration</strong> tab, select "Mixed Mode" authentication. <br>
         Doing so will allow you to set a password for "<strong>System Administrator (sa)</strong>" user.<br>
        <br>
      <img src="https://www.visual-expert.com/images/database-engine-configuration.png" alt="Database Engine Configuration"><br></li><br>
           <li>Click on <strong>"Add Current User"</strong> to set the current user as Administrator for this SQL Server instance. Then, click <strong>"Next"</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/add-current-user-as-administrator.png" alt="Add Current User as Administrator"><br></li><br>
      <li>Arriving at the <strong>'Feature Configuration Rules'</strong> window, make sure all the <strong>Rule(s)</strong> pass the installer scanning test. Then, click <strong>'Next'</strong>.<br>
        <br>
      <img src="https://www.visual-expert.com/images/feature-configuration-rules.png" alt="Feature Configuration Rules"><br></li><br>
      <li>All configuration steps have been completed. Click "Install" to start the installation.<br>
        <br>
      <img src="https://www.visual-expert.com/images/install-sql-server-2019.png" alt="Install SQL Server 2019 Developer Edition"><br></li><br>
      <li>The installation begins.<br>
        <br>
      <img src="https://www.visual-expert.com/images/installation-begins.png" alt="Installation of SQL Server 2019 Begins"><br></li><br>
      <li>The installation of SQL Server 2019 Developer Edition is completed.<br>
        <br>
      <img src="https://www.visual-expert.com/images/sql-server-2019-installation-completed.png" alt="Installation of SQL Server 2019 Completed"><br></li><br>
      </ol>
      <section class="section pl-20 pr-20" style="max-width: 1084px;">
          <div class="row">
            <div class="col-md-10 default-bg clearfix bg-blue-gradient ">
              <div class="call-to-action pl-10 pv-10">
                <div class="row">
                  <div class="col-sm-12 text-center">
                    <h1>Analyze your SQL Server T-SQL Code</h1>
                    <p class="lead">Download <strong>Visual Expert Free Trial</strong> to Analyze Cross-References, Document your SQL&nbsp;Server&nbsp;Code, Generate Diagrams and CRUD Matrix, and&nbsp;much&nbsp;more.
                    </p>
                     <p><br>
                    <a href="https://www.visual-expert.com/EN/download_VE-for-SQL-Server-trial.html" class="btn btn-default btn-lg btn-animated">Try Visual Expert <i class="fa fa-download pl-20"></i></a></p>
                  </div>
                  
                </div>
              </div>
            </div>
          </div>
        </section>
    
