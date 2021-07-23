
# Patient Information System

The project Patient Information System is built with substrate. The main Objective of Patient Information System is to manage the details of patient, doctor and also manage the patient appointment.

## Why use it?
The purpose of this system is to build an application program to reduce the manual work for keep to track patient information and managing the patient.

## Modules of Patient Information System
- Patient Module :
  The main objective of this module is to store the details of patient. Admin can add new patient records. Admin can see the patient details.
- Doctor Module :
  The main objective of Doctor module is to store the doctor information like Name, Contact No, Address, Specialization etc. Admin can add new doctor records.
- Appointment Module:
  The main aim for developing this module is to manage appointment. So all appointment will be managed by Admin. Admin can see the all appointment details.

## Installation 
Simply go through [substrate.dev](https://substrate.dev/) and follow the installation steps. Also try tutorials like add pallet in its own crate etc.

Install the Node Template:
You should already have version v3.0.0 of the Substrate Node Template compiled on your computer and completed the Create Your First Substrate Chain Tutorial. 

### Add Doctor pallet
```bash
cd pallets
git clone -b v3.0.0 --depth 1 https://github.com/substrate-developer-hub/substrate-pallet-template doctor
``` 
### To add more dependencies just go through [substrate calculator](https://github.com/MohiniSalunkhe88/Calculator/blob/main/README.md)


Once you added dependencies then interact with the pallet
```bash
cargo build --release
```
After the build succeeds, you can start the node
```bash
./target/release/node-template --dev --tmp
```
 Once your node is running, At that time go to [polkadot.js](https://polkadot.js.org/apps/)

#### Click on Developer -> extrinsics -> doctor

![Doctor](https://user-images.githubusercontent.com/85221851/126740577-0a2f64e3-1962-4967-bdc9-bfe4e90fe217.png)

Click on Network -> explorer

![doctorinfo](https://user-images.githubusercontent.com/85221851/126741020-c67e742a-f5ca-44f7-b3c2-77532fa988f8.png)

- The same process will be followed for the Doctor and Appointment pallet.
