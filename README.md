Download Link: https://assignmentchef.com/product/solved-msds7330-assignment-5
<br>



<ul>

 <li>In general, normalizing a single flat-file database results in which of the following?

  <ol>

   <li>Many tables.</li>

   <li>Reduced data redundancy.</li>

   <li>No INSERT, DELETE or UPDATE anomalies.</li>

   <li>All of the above.</li>

   <li>None of the above.</li>

  </ol></li>

 <li>Normalization

  <ol>

   <li>has no impact on performance.</li>

   <li>is necessary for read-only databases.</li>

   <li>sets the business rules.</li>

   <li>is a technical exercise that does not change thebusiness rules.</li>

  </ol></li>

 <li>Normalization is required to

  <ol>

   <li>prevent updates by unauthorized personnel.</li>

   <li>update multiple instances of data at the same time.</li>

   <li>make sure the same data is stored in multiplelocations.</li>

   <li>preserve data quality.</li>

  </ol></li>

 <li>In a read only database

  <ol>

   <li>denormalization is common in order to provideefficient report generation.</li>

   <li>normalization is required to prevent update anoma-lies.</li>

   <li>normalization has no impact on reads.</li>

   <li>denormalization is performed to speed up writes.</li>

  </ol></li>

 <li>A table normalized to first normal form (1NF) commonly

  <ol>

   <li>includes more attributes than the non-normalizedversion.</li>

   <li>contains more records than the non-normalizedversion.</li>

   <li>contains less records than the non-normalized ver-sion.</li>

   <li>has no redundant data.</li>

  </ol></li>

 <li>A relation is in first normal form (1NF) if

  <ol>

   <li>at least one attribute in every row contain only onesingle (atomic) value.</li>

   <li>every non-key attribute is fully functionally depen-dent on the primary key.</li>

   <li>at least one attribute in every row can contain morethan one value (multivalued).</li>

   <li>every attribute in every row can contain only one</li>

  </ol></li>

</ul>

single (atomic) value.

<ul>

 <li>A relation is in first normal form (1NF) if

  <ol>

   <li>it doesn’t contain an determinants.</li>

   <li>it doesn’t contain any repeating groups.</li>

   <li>it doesn’t contain any null values in primary keyfields.</li>

  </ol></li>

</ul>

<table width="679">

 <tbody>

  <tr>

   <td width="207">2016 Sohail Rafiqi, Ph.D. All Rights Reserved.</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>it doesn’t contain any functional dependences.</li>

</ol>

<ul>

 <li>A relation is in second normal form (2NF) if

  <ol>

   <li>it is in 1NF and every key attribute is fully func-tionally dependent on the primary key.</li>

   <li>it is in 1NF and every attribute is fully functionallydependent on the primary key.</li>

   <li>it is in 1NF and every non-key attribute is fullyfunctionally dependent on the primary key.</li>

   <li>it is in 1NF and no non-key attribute is transitively</li>

  </ol></li>

</ul>

dependent on the primary key.

<ul>

 <li>A relation is in third normal form (3NF) if

  <ol>

   <li>it is in 1NF and no non-key attribute is transitivelydependent on the primary key.</li>

   <li>it is in 2NF and no non-key attribute is transitivelydependent on the primary key.</li>

   <li>it is in 1NF and no non-key attribute is fullyfunctionally dependent on the primary key.</li>

   <li>it is in 2NF and no non-key attribute is fully</li>

  </ol></li>

</ul>

functionally dependent on the primary key.

<ul>

 <li>In fourth normal form (4NF)

  <ol>

   <li>All occurrences of an entity must contain the samenumber of attributes.</li>

   <li>All non-key fields must be a function of the key.</li>

   <li>All non-key fields must not be a function of othernon-key fields.</li>

   <li>A row must not contain two or more independentmulti-valued facts about an entity.</li>

  </ol></li>

 <li>When you normalize a relation by breaking it into two smaller relations, what must you do to maintain data integrity? [Hint: more than one answer is correct.]

  <ol>

   <li>Link the relations by a common field.</li>

   <li>Remove any functional dependencies from bothrelations.</li>

   <li>Assign both relations the same primary key field(s).</li>

   <li>Create a primary key(s) for the new relation.</li>

  </ol></li>

 <li>Table I is in which normal form?

  <ol>

   <li>First Normal Form (1NF)</li>

   <li>Second Normal Form (2NF)</li>

   <li>Third Normal Form (3NF)</li>

   <li>Fourth Normal Form (4NF)</li>

  </ol></li>

 <li>In Table I, which of the following is apparently true?

  <ol>

   <li>StudentID → TutorID</li>

   <li>CourseID → Room, Topic</li>

   <li>CourseID → TutorID</li>

   <li>CourseID → Topic</li>

  </ol></li>

 <li>Normalization ensures that each fact (data) is

  <ol>

   <li>stored in exactly one location.</li>

   <li>stored in multiple locations and updated simulta-neously.</li>

   <li>updated in all locations simultaneously.</li>

   <li>not null.</li>

  </ol></li>

 <li>In discussing normal form, a key is

  <ol>

   <li>a unique identifier for a row in a table, used toselect the row in queries.</li>

   <li>a set of attributes that describe an instance of anentity.</li>

   <li>an object defined in the system model about whichdata is stored in the database.</li>

   <li>a set of attributes that cannot be used to uniquelyidentify a row in a table.</li>

  </ol></li>

 <li>The same fact (data) that is stored in multiple locations may become

  <ol>

   <li></li>

   <li></li>

   <li>a foreign key.</li>

   <li></li>

  </ol></li>

 <li>To alter a product name requires the name to be changed in 5 different places. This is an example of a potential

  <ol>

   <li>DELETE anomaly.</li>

   <li>INSERT anomaly.</li>

   <li>UPDATE anomaly.</li>

   <li>CREATE anomaly.</li>

  </ol></li>

 <li>A school database’s Students table contains the name and address details of each student. However there are many brothers and sisters in the school who live at the same address. Splitting the address details into their own table would occur when normalizing the Students table into:

  <ol>

   <li>1NF</li>

   <li>2NF</li>

   <li>3NF</li>

   <li>4NF</li>

  </ol></li>

 <li>In a normalized table, the attribute <em>A1 </em>is functionally dependent on the attribute Which os the following is true?

  <ol>

   <li>There can be repeating values in the <em>A1 </em></li>

   <li>The <em>A2 </em>column is a unique identifier.</li>

   <li>Each value for <em>A2 </em>identifies a single value of</li>

   <li>All of the above.</li>

   <li>None of the above.</li>

  </ol></li>

</ul>




<ul>

 <li>A table contains data about products and customers. 21) During normalization it is first noticed that each time a Splitting this table into two would occur when normal- particular value in attribute p occurs attribute q has the izing the table into: same value. Which normal form is being considered?

  <ol>

   <li>1NF a) 1NF</li>

   <li>2NF b) 2NF</li>

   <li>3NF c) 3NF</li>

   <li>4NF d) 4NF</li>

  </ol></li>

</ul>

<table width="480">

 <tbody>

  <tr>

   <td width="57">U1</td>

   <td width="60">St1</td>

   <td width="53">23.02.03</td>

   <td width="50">Tut1</td>

   <td width="40">GMT</td>

   <td width="42">629</td>

   <td width="42">4.7</td>

   <td width="62">Deumlich</td>

   <td width="74"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e1959495d0a187898383cf8289">[email protected]</a></td>

  </tr>

  <tr>

   <td width="57">U2</td>

   <td width="60">St1</td>

   <td width="53">18.11.02</td>

   <td width="50">Tut3</td>

   <td width="40">GIn</td>

   <td width="42">631</td>

   <td width="42">5.1</td>

   <td width="62">Zehnder</td>

   <td width="74"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c6b2b3b2f586a0aea4a4e8a5ae">[email protected]</a></td>

  </tr>

  <tr>

   <td width="57">U1</td>

   <td width="60">St4</td>

   <td width="53">23.02.03</td>

   <td width="50">Tut1</td>

   <td width="40">GMT</td>

   <td width="42">629</td>

   <td width="42">4.3</td>

   <td width="62">Deumlich</td>

   <td width="74"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b5c1c0c184f5d3ddd7d79bd6dd">[email protected]</a></td>

  </tr>

  <tr>

   <td width="57">U5</td>

   <td width="60">St2</td>

   <td width="53">05.05.03</td>

   <td width="50">Tut3</td>

   <td width="40">PhF</td>

   <td width="42">632</td>

   <td width="42">4.9</td>

   <td width="62">Dmmlers</td>

   <td width="74"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="582c2d2c6b183e303a3a763b30">[email protected]</a></td>

  </tr>

  <tr>

   <td width="57">U4</td>

   <td width="60">St2</td>

   <td width="53">04.07.03</td>

   <td width="50">Tut5</td>

   <td width="40">AVQ</td>

   <td width="42">621</td>

   <td width="42">5.0</td>

   <td width="62">SwissTopo</td>

   <td width="74"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="106465642550767872723e7378">[email protected]</a></td>

  </tr>

 </tbody>

</table>

<table width="480">

 <tbody>

  <tr>

   <td width="57">CourseID</td>

   <td width="60">StudentID</td>

   <td width="53">Date</td>

   <td width="50">TutorID</td>

   <td width="40">Topic</td>

   <td width="42">Room</td>

   <td width="42">Grade</td>

   <td width="62">Book</td>

   <td width="74">TutEmail</td>

  </tr>

 </tbody>

</table>

TABLE I STUDENT-TUTOR TABLE