# Aksana Bebesh

**Fullstack Software developer (PHP, JS, MySQL, Postgres, React)**

<hr />

## Contacts:

 Poland (Lodz) <br>
*linkedin:* <a href="https://www.linkedin.com/in/oksana-bebesh1984/">https://www.linkedin.com/in/oksana-bebesh1984/</a><br>
*telegram:* @oksanabebesh <br>
*skype:* live:kseniia_25<br>
*mail:* <a href="mailto:oksana.bebesh1984@gmail.com">oksana.bebesh1984@gmail.com</a><br>
*phone:* +48 78 0003 744<br>

<hr />

## Brief Profile
<p>Full stack developer with 2.5 years of experience in building web applications based on web technologies: PHP(Symfony, Laravel), CMS (WordPress), MySQL(procedures, triggers), PostgreSQL,
AWS SQS, HTML5, CSS, JavaScript, React, NodeJS, Familiar with Docker (docker compose), Git (Github), Jira.</p>

<hr />

## Skills and Proficiency:


1) PHP Advanced
   
2) Symfony Intermediate
 
3) MySQL Advanced
 
4) JavaScript Advanced
 
5) HTML Advanced
 
6) CSS Advanced
 
7) Git Advanced
 
8) WordPress Advanced
 
9) React Intermediate
 
10) Node.js Basic
 
11) AWS SQS Basic 

<hr />

## Projects

<a href="https://rolling-scopes-school.github.io/oksanabebesh-JSFEPRESCHOOL2023Q2/js-30-image-gallery/">image-gallery</a>

<a href="https://rolling-scopes-school.github.io/oksanabebesh-JSFEPRESCHOOL2023Q2/js30-media/">small-media</a>

<a href="https://rolling-scopes-school.github.io/oksanabebesh-JSFEPRESCHOOL2023Q2/js30-memo-game/">memo-game</a>

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

## Courses
In 2009 I studied in Cisco® Networking Academy. I have got next diploma: <br>
•CCNA 1 Networking Basics <br>
•CCNA 2 Router and Routing Basics <br>
•CCNA 3 Switching Basics and Intermediate Routing <br>


<hr />

## Languages <br/>
English B1 <br/>
Russian native <br/>
