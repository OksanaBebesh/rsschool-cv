# Aksana Bebesh Poland (Lodz) <br/>

<hr>
## Fullstack Software developer (PHP, JS, MySQL, Postgres, React)<br />
<hr>
## Languages
### English B1
### Russian native

*linkedin:* <a href="https://www.linkedin.com/in/oksana-bebesh1984/">https://www.linkedin.com/in/oksana-bebesh1984/</a><br>
*telegram:* @oksanabebesh <br>
*skype:* live:kseniia_25<br>
*mail:* <a href="mailto:oksana.bebesh1984@gmail.com">oksana.bebesh1984@gmail.com</a><br>
*phone:* +48 78 0003 744<br>

<hr>
## Brief Profile
<p>Full stack developer with 2.5 years of experience in building web applications based on web technologies: PHP(Symfony, Laravel), CMS (WordPress), MySQL(procedures, triggers), PostgreSQL,
AWS SQS, HTML5, CSS, JavaScript, React, NodeJS, Familiar with Docker (docker compose), Git (Github), Jira.</p>

<hr>
## Examples of code  
```JavaScript
StorageModule.groupStatesUpdate = () => {  
    const data = StorageModule.getData();
    const newdata = data
                    .map(group => {
                       group.states = []
                       return group
                    })
                    .map(group =>{                          
                          group.states = group.rows.map(row => row[1]);                          
                          return group;
                    })
                    .map(group =>{
                          group.stateAccept = ( group.states.includes('принят') ) ? 'Accept' : ''
                          return group;
                    });
    StorageModule.setData(newdata);
}
```

*SQL Query For finding errors with helth cards, when cards have two patients*<br/>
<pre><code>
  SELECT DISTINCT  t.PHN,t.PatientLastName,t.PatientFirstName,t.Birthdate  
    FROM tmp_migr.tblpatient t
     JOIN
    (SELECT  DISTINCT p.PHN AS pphn,p.PatientLastName AS pLN,p.PatientFirstName AS pFN,p.Birthdate AS pBRTH
    FROM tmp_migr.tblpatient p 
    ) as rrr 
   ON t.PHN=rrr.pphn AND  t.PatientLastName!=rrr.pLN AND t.Birthdate!=rrr.pFN and  t.Birthdate!=rrr.pBRTH;
</code></pre>
<hr />

<hr>
## Courses
In 2009 I studied in Cisco® Networking Academy. I have got next diploma:
•CCNA 1 Networking Basics
•CCNA 2 Router and Routing Basics
•CCNA 3 Switching Basics and Intermediate Routing
