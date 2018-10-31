## Instructors

<table style="table-layout: fixed; font-size: 88%;">
  <thead>
    <tr>
      <th style="width: 25%;"><img src="https://people.eecs.berkeley.edu/~dawnsong/dawn-berkeley.jpg" alt="Dawn Song"></th>
      <th style="width: 25%;"><img src="http://www.cs.umd.edu/~akosba/webpage/p_o.png" alt="Ahmed Kosba"></th>
      <th style="width: 25%;"><img src="https://people.eecs.berkeley.edu/~jian.liu/images/1.jpg" alt="Jian Liu"></th>
      <th style="width: 25%;"><img src="http://legacydirs.umiacs.umd.edu/~zhangyp/photo.jpeg" alt="Yupeng Zhang"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
      <td><a href="http://www.cs.umd.edu/~akosba/">Ahmed Kosba</a></td>
      <td><a href="https://people.eecs.berkeley.edu/~jian.liu/">Jian Liu</a></td>
      <td><a href="http://legacydirs.umiacs.umd.edu/~zhangyp/">Yupeng Zhang</a></td>
    </tr>
    <tr>
      <td>Professor, <a href="https://eecs.berkeley.edu/">EECS</a></td>
      <td>Postdoc, <a href="https://eecs.berkeley.edu/">EECS</a></td>
      <td>Postdoc, <a href="https://eecs.berkeley.edu/">EECS</a></td>
      <td>Postdoc, <a href="https://eecs.berkeley.edu/">EECS</a></td>
    </tr>
  </tbody>
</table>

## Volunteer Teaching Assistant

Tiancheng Xie

## Lectures

**Time**: Monday 4:00--6:00 pm

**Location**: Soda 310

## Piazza and Mailing List

If you are taking the class, please sign up for the [course mailing list](https://groups.google.com/forum/#!forum/cs-294-151-f18-all) for future announcements. You can add yourself to the list by clicking the link and "Join group". Be sure to be signed in to your Google account.

If you do not plan to take the class, but are interested in getting announcements about guest speakers in class, and more generally, blockchain talks at Berkeley, please sign up for the [talk announcement mailing list](https://groups.google.com/forum/#!forum/berkeley-blockchain) for future announcements.

Course announcements will be announced through Piazza. If you are enrolled in the class, [sign up on Piazza](
https://piazza.com/berkeley/fall2018/cs294151).

## Course description
Blockchain has the potential to transform many segments of the industry and society. In this course, we plan to cover advanced topics on blockchain, smart contracts, and cryptoeconomics. We will discuss recent research papers and techniques on scalability, privacy, different consensus mechanisms, attacks on blockchain and smart contracts and mitigation against them, applications of blockchain and smart contracts, and cryptoeconomics. 

The course is 3-units, and will consist of several research paper readings per week, in-class discussions of the papers, and a large course project per project group.

<p>Course intro <a href="https://drive.google.com/open?id=1Jc97zAUMt3Yn_tt9f738TswBIiY29Igg">slides</a>.</p>

## Syllabus
<table style="table-layout: fixed; font-size: 88%;">
  <thead>
    <tr>
      <th style="width: 5%;">Date</th>
      <th style="width: 10%;">Section</th>
      <th style="width: 40%;">Topic</th>
      <th style="width: 55%;">Readings</th>
      <th style="width: 20%;">Talk</th>
      <th style="width: 10%;">Deadlines</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>08/27</td>
      <td rowspan="2">Introduction</td>
      <td>
      Introduction and 
      Logistics
         <ul>
          <li>History and overview of blockchains</li>
          <li>Nakamoto consensus and Bitcoin</li>
          <li>Bitcoin formalism</li>
        </ul>
      </td>
      <td>
         <ul>
          <li><a href="https://bitcoin.org/bitcoin.pdf">Bitcoin</a></li>
          <li><a href="https://d28rh4a8wq0iu5.cloudfront.net/bitcointech/readings/princeton_bitcoin_book.pdf">Narayanan et al. (first two chapters)</a></li>
        </ul>
      </td>
      <td><a href="http://www.cs.umd.edu/~kartik/">Kartik Nayak</a>
      <a href="https://drive.google.com/open?id=1mYFN8bFbXiGbVKbfisBcYAB7hIRCFnQI">(Slides)</a></td>      
      <td></td>
    </tr>
    <tr>
      <td>09/03</td>
      <td>No Class, Labor Day</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>09/10</td>
      <td rowspan="4">Scalability</td>
      <td>Byzantine fault tolerance (BFT) Concensus</td>
      <td></td>
      <td><a href="https://research.vmware.com/researchers/dahlia-malkhi">Dahlia Malkhi</a>
      <a href="https://drive.google.com/open?id=1jBkKkLgaAH2z_JdRNHVusTN75RXqPF-a">(Slides)</a></td>
      <td>Team Formation Due 09/10</td>
    </tr>
    <tr>
      <td>09/17</td>
      <td>Block DAG Protocols</td>
      <td>
         <ul>
          <li><a href="https://eprint.iacr.org/2013/881.pdf">Background Reading: GHOST</a></li>
          <li><a href="https://arxiv.org/abs/1805.03870">Conflux</a></li>
          <li><a href="https://fc15.ifca.ai/preproceedings/paper_101.pdf">Inclusive Blockchain</a></li>
          <li><a href="https://eprint.iacr.org/2016/1159.pdf">SPECTRE</a></li>
           <li><a href="https://eprint.iacr.org/2018/104.pdf">PHANTOM</a></li>
        </ul>
      </td>
      <td> <a href="http://www.cs.toronto.edu/~fanl/">Fan Long</a>
      <a href="https://drive.google.com/open?id=17DNyCCcXf-OIvhNGX8NHZhMKJtM94qcZ">(Slides)</a></td>
      <td></td>
    </tr>
    <tr>
      <td>09/24</td>
      <td>Horizontal scaling
        <ul>
          <li>Revisiting scalability</li>
          <li>Challenges for horizontal scaling</li>
          <li>Blockchain sharding</li>
          <li>Asynchronous execution</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="https://docs.zilliqa.com/whitepaper.pdf">ZILLIQA</a></li>
          <li><a href="https://eprint.iacr.org/2017/406.pdf">OmniLedger</a></li>        
          <li><a href="https://arxiv.org/abs/1708.03778">Chainspace</a></li>
        </ul>
      </td>
      <td>Jian Liu
      <a href="https://drive.google.com/file/d/1mFGzMMVcNk-QJUAqqNzhUOvI5XaxlTSS/view?usp=sharing">(Slides)</a></td>
      <td>Project Proposals Due 09/30</td>
    </tr>
    <tr>
      <td>10/01</td>
      <td>Non-PoW Consensus Approaches
        <ul>
          <li>PoS</li>
          <li>Verifiable Delayed functions</li>
          <li>etc</li>
        </ul>
      </td>
      <td><ul>
          <li>Verifiable Delay Functions <a href="https://eprint.iacr.org/2018/601.pdf">1</a>, <a href="https://eprint.iacr.org/2018/627.pdf">2</a>, <a href="https://eprint.iacr.org/2018/623.pdf">3</a>, <a href="https://eprint.iacr.org/2018/712.pdf">4</a> </li>
          <li><a href="https://people.csail.mit.edu/nickolai/papers/gilad-algorand-eprint.pdf">Algorand</a></li>        
          <li><a href="https://eprint.iacr.org/2016/919.pdf">Snow White</a></li>
          <li><a href="https://eprint.iacr.org/2016/889.pdf">Ouroboros</a></li>
        </ul>
      </td>
      <td>
      <a href="https://crypto.stanford.edu/~buenz/">Benedikt Bünz</a>
      <a href="https://drive.google.com/open?id=1_GpWaxUwChKR9Owq-xDqe5z6RvCfWzW4">(Slides)</a></td>
      <td></td>
    </tr>
    <tr>
      <td>10/08</td>
      <td rowspan="3">Privacy</td>
      <td>Zero-knowledge proofs in practice
         <ul>
          <li>Privacy in decentralized cryptocurrencies</li>
          <li>zk-SNARKs (constructions, tools and applications in cryptocurrency)</li>
          <li>New ZK proof constructions</li>
        </ul>
      </td>
      <td> 
        <ul>
          <li><a href="http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf">ZeroCash</a></li>
          <li><a href="https://eprint.iacr.org/2017/1066.pdf">BulletProofs</a></li>
          <li><a href="https://eprint.iacr.org/2018/046.pdf">zk-STARKs</a></li>
          Background Readings posted on Piazza
        </ul>
      </td>
      <td>Ahmed Kosba 
      <a href="https://drive.google.com/open?id=1ZcsPtRPt8UETYgwso6AyEDP2t-RvH7ce">(Slides)</a></td>
      <td></td>
    </tr>
    <tr>
      <td>10/15</td>
      <td>Secure multi-party computation (SMC) 
        <ul>
          <li>Background and definitions</li>
          <li>Existing contrustions: garbled circuit and GMW protocol</li>
          <li>Privacy-preserving blockchain using SMC</li>
          <li>Achieving fairness in SMC using blockchain</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=GjhvJxelIVQ">Yao's Garbled Circuit</a></li>
          <li><a href="https://www.youtube.com/watch?v=4YwvZaA9IEg">GMW protocol</a></li>       
          <li><a href="https://kodu.ut.ee/~swen/courses/crypto-ii/2008/cleve1986.pdf"> Limits on the Security of Coin Flips When Half the Processors are Faulty </a></li>
          <li><a href="https://eprint.iacr.org/2014/129.pdf">How to Use Bitcoin to Design Fair Protocols</a></li>
        </ul>
      </td>
      <td>Yupeng Zhang
        <a href="https://drive.google.com/open?id=1QQAfKJzRxXqMOLIWCE0i0P4B7CWfZP8x">(Slides)</a></td></td>
      <td></td>
    </tr>
    <tr>
      <td>10/22</td>
      <td>Secure hardware</td>
      <td>
        <ul>
          <li><a href="https://eprint.iacr.org/2016/086.pdf">SGX Explained (Sections 1 and 4)</a></li>
          <li><a href="https://arxiv.org/abs/1804.05141">Ekiden</a></li>       
        </ul>
     </td>
      <td>
        <ul>
          <li><a href="https://people.eecs.berkeley.edu/~dkohlbre/">David Kohlbrenner</a></li>
          <li>Dawn Song</li>       
        </ul>
      </td>
      <td></td>
    </tr>
    <tr>
      <td>10/29</td>
      <td rowspan="1">Applications</td>
      <td>Applications & secure contract programming</td>
      <td>
         <ul>
          <li><a href="https://eprint.iacr.org/2017/1090.pdf">Hydra</a></li>
          <li><a href="https://eprint.iacr.org/2016/1007.pdf">Survey of attacks on smart contracts</a></li>
         </ul>
      </td>
      <td>Ahmed Kosba</td>
      <td>Project Progress Report Due 10/29</td>
    </tr>
    <tr>
      <td>11/05</td>
      <td rowspan="3">CryptoEconomics</td>
      <td></td>
      <td>
        <ul>
          <li><a href="http://christophertonetti.com/files/papers/JonesTonetti_DataNonrivalry.pdf">Nonrivalry and the Economics of Data</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11/12</td>
      <td>No Class, Veterans Day</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11/19</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11/26</td>
      <td>Project Presentations</td>
      <td></td>
      <td></td>
      <td></td>
      <td>Project Report Due 11/30</td>
    </tr>
  </tbody>
</table>


## Class format and project
This is a project oriented class. Each lecture will focus on one of the research topics on blockchain and cryptocurrencies. Each week, students are expected to complete reading assignments before class and participate actively in class discussion.

Students will also form project groups and complete a high-impact research project. The final project/deliverable will be a team presentation and a paper/report on the project.

## Grading

<ul>
  <li>20% class participation</li>
  <li>20% weekly reading assignment</li>
  <li>60% project</li>
</ul>

## Enrollment information

Enrollment is very limited. If you require an authorization code to enroll in the class, please fill out **[this form](https://docs.google.com/forms/d/e/1FAIpQLSc0-A5kOI_ykJOOkT2bfhyG3Ny6qFr4S-odxnuO5mC6UQWn1w/viewform?ts=5b53bd5c)**. Accepted students will be given instructor codes to register for the class. Decisions for admission will be released on a rolling basis. Due to limited space, please apply as soon as possible.

## Supplemental Reading

[Bitcoin and Cryptocurrency Technologies](http://bitcoinbook.cs.princeton.edu/) - Free introductory book available on website


## Additional Notes

For students who need computing resources for the class project, we recommend you to look into AWS educate program for students. You’ll get 100 dollar’s worth of sign up credit. Here’s the [link](https://aws.amazon.com/education/awseducate/apply/).
