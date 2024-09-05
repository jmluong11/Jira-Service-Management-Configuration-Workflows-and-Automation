![Jira-Service-Management-logo](https://i.imgur.com/kyFipS7.png)

<h1> Jira Service Management: Configuration, Workflows and Automation </h1>

<p> This project aims to enhance IT support processes by leveraging the advanced capabilities of Jira. The focus will be on carefully configuring Jira settings, developing streamlined workflows, and implementing intelligent automation. Through customization of issue types, fields, screens, and automation rules, a clear and efficient process will be established to guide each ticket from initial reporting to resolution.</p>

</p>

<h2>Objectives</h2>

<h4> Streamline Ticket Management: </h4>

- Simplify the process of creating, tracking, and managing tickets through customized workflows and fields tailored to various types of IT support requests.

<h4> Automate Routine Tasks: </h4>

- Implement automation rules to handle repetitive tasks such as ticket assignments, status updates, and notifications.

<h4> Enhance Communication: </h4>

- Facilitate better communication within the support team and with end-users through automated notifications and updates.

</p>

<h2> Environments and Technologies Used </h2>

- Jira Service Management 
- Windows 11

<h2> Customizing Issue Types </h2>

<p>Jira allows you to customize the types of issues that can be created within your project. This is essential for categorizing the different kinds of requests and problems your help desk will handle.</p>

![Issue types](https://i.imgur.com/jaXWYBA.png)

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3> Standard Issue Types for IT Help Desk: </h3>

<p><strong> 1. Bug Report </strong></p>

![Bug report](https://i.imgur.com/F2E6Kmj.png)

</p>
</p>

<p><strong> 2. Hardware Request </strong></p>


![Hardware Req](https://i.imgur.com/84uvvJk.png)


</p>
</p>

<p><strong> 3. Software Installation </strong></p>

![Software](https://i.imgur.com/84uvvJk.png)

</p>
</p>

<p><strong> 4. Network Issue  </strong></p>

![Network](https://i.imgur.com/l3hqBOd.png)

</p>
</p>

<p><strong> 4. Access Request  </strong></p>

![access](https://i.imgur.com/VAkC1Gz.png)

<br>

<h2> Defining a Workflow </h2>

<p> A workflow defines the lifecycle of an issue, from creation to resolution. Customizing the workflow allows you to mirror your organization's process for handling IT support requests.</p>

<img width="1003" alt="workflow" src="https://i.imgur.com/TXBC7q7.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Standard Workflow Stages for IT Help Desk: </h3>

<img width="624" alt="diagram" src="https://i.imgur.com/YyzxiOj.png">

<br>
<br>

<p><strong>Open:</strong> The initial status of a new issue.</p>
<p><strong>In Progress:</strong>The issue is being worked on by IT staff.</p>
<p><strong>Awaiting User:</strong> Waiting for more information or confirmation from the user.</p>
<p><strong>Resolved:</strong> The issue has been addressed, awaiting closure.</p>
<p><strong>Closed:</strong> The issue is fully resolved and closed.</p>

<br>

![diagram border](https://i.imgur.com/6QHBinc.png)

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h2>Custom Fields</h2>

<p>Custom fields allow you to capture specific information related to different issue types. </p>

![custom fields](https://i.imgur.com/HYOI6km.png)


<p><strong>Severity Level:</strong> Helps prioritize issues based on their impact on the business.</p>

<p><strong>Affected System:</strong> Identifies which system or application is impacted by the issue. </p>

<p><strong>Reported By:</strong> Captures whether the issue was reported by an employee, customer, or vendor. </p>
  
<p><strong>Expected Resolution Time:</strong> Provides an estimate of how long it will take to resolve the issue, which can be crucial for managing expectations.</p>

<p><strong>Root Cause Analysis:</strong> A text field for documenting the underlying cause of the issue once it has been identified. This is valuable for preventing future occurrences.</p>

<br>

<h2>Customizing Screens</h2>

<p>Screens in Jira determine which fields are displayed to users when they create, view, or edit an issue. Customizing these screens allows you to ensure that users are prompted for all relevant information when reporting an issue or moving it through its lifecycle.</p>


![Screens](https://i.imgur.com/mhndw2R.png)
