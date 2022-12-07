# EHR 2.0

## Problem Statement
Over decades, medical facilities have evolved elegantly. Still most of us are the witness of the fact that whenever we see a doctor, we need to put forward our medical file in front of him/her. Our file contains our previous prescriptions, medical reports, X-Rays, MRIs etc. It is a tedious task to keep a record of all these.

Currently, EHR systems in hospitals are problematic. They are hacked often (just google 'ehr systems hacked'), are not transparent, and don't keep a record of all changes to the patient record.

## Aim of the Project
We aim to provide a digital solution to this problem so that next time when you visit your doctor, you don’t need to carry your medical file. We will be using Blockchain technology to store the patient records. This will ensure that the information remains secure while being decentralized across different peers.

The basic idea is to use Blockchain for storing patient records. The workflow would be as follows:
1. Anyone can register on the Blockchain network as a doctor or a patient.
2. Whenever a patient visits a doctor, the doctor will have the required permissions to store the diagnosis and medical logs in the patient’s record which would be stored in distributed ledgers across the Blockchain network.
3. The doctor would be required to sign in the transaction (which would be cryptographically encrypted with his private key) to create and modify the records of a patient (who would be uniquely identified by a patient ID).
4. The medical records of a patient will be accessible from any hospital.


🆁🅴🆀🆄🅸🆁🅴🅼🅴🅽🆃🆂

1.Install nodeJs

* [Node JS](https://nodejs.org/en/download/)

2.Install Ganache

* [Ganache Truffle](https://www.trufflesuite.com/ganache)

3.Add Metamask Extension in Browser

* [Metamask Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en-US)

4. open cmd in project directory

  npm install --force


5.open cmd/terminal as Administrator and type

	npm install -g truffle
	
6.open Ganache
 
 *  New Workspace
 *  AddProject
 *  Select truffle-config.js in Project Directory
 *  Save Workspace

7.Compile and migrate Contracts
   ```
   truffle migrate
   ```
## Development server

Run `ng serve -o` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.