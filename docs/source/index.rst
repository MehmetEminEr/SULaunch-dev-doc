Welcome to Sulaunch's developer documentation!
================================================

**SuLaunch** is an ENS491/492 project offered at the Sabanci University as a graduation project. The main aim of this project is to introduce Blockchain technology to CS enthusiasts and wants to explore new technology.

This project aims to create the foundation for the utilization of blockchain technology in Sabanci University through an utility token (SUC) deployed on one of the EVM compatible blockchains. The main priority is to provide a fundraising platform for students to propose their projects and distribute their project’s tokens for funds via the auction mechanism provided by our system. The process will be as basic as possible for users to use blockchain technology, most of the key features of our project will be automated through the smart contracts and the backend server.

One of the key points of this part of the project is to protect the ideas of the project proposers as in the real world, fundraising can be vulnerable to the theft of ideas. The project provides a hybrid solution where both traditional databases and a blockchain are utilized to provide a safety measure. This is achieved through saving the hash of the project details in the blockchain and commercialized versions of the project details in the database. This lets users be able to show the ownership of the document through their wallet and the logs in the blockchain by our web application during the applying process.

The motivation for the project lies in the safety of the project’s owner’s rights, decentralization of the funding mechanisms around the schools, and providing a solid foundation for the later blockchain use cases which can be utilized through SUC.

This is a code documentation for developers. Since it is about how the platform works, It is recommended that you read the `User Documentation <https://sulaunch-1.gitbook.io/sulaunch/>`_ first.

Contents
--------

.. toctree::
   :maxdepth: 1

   setup

.. toctree::
   :maxdepth: 2
   :caption: Backend

   backend/Backend Introduction
   backend/Constants
   backend/Data Context
   backend/Data Transfer Objects


.. toctree::
   :maxdepth: 1
   :caption: Controllers
   :name: controllers

   backend/controllers/Controllers Introduction
   backend/controllers/Authentication Controller
   backend/controllers/Event Debug Controller
   backend/controllers/User Controller
   backend/controllers/Project Controller

.. toctree::
   :maxdepth: 1
   :caption: Models
   :name: models

   backend/models/Projects
   backend/models/ProjectPermission
   backend/models/Rating
   backend/models/User

.. toctree::
   :maxdepth: 1
   :caption: Request
   :name: request

   backend/request/ProjectPermissionRequest
   backend/request/ProjectRequest
   backend/request/UserLoginRequest
   backend/request/UserRegisterRequest

.. toctree::
   :maxdepth: 1
   :caption: Response
   :name: response

   backend/response/ServiceResponse

.. toctree::
   :maxdepth: 1
   :caption: Services
   :name: services

   backend/services/AuthenticationService
   backend/services/ChainInteractionService
   backend/services/IpfsInteractionService

.. toctree::
   :maxdepth: 1
   :caption: DTOS
   :name: dtos

   backend/dtos/AdminChangeEvent
   backend/dtos/AuctionFinishedEvent
   backend/dtos/AuctionStartedEvent
   backend/dtos/BidSubmissionEvent
   backend/dtos/ClaimTokensEvent
   backend/dtos/CreateAuctionEvent
   backend/dtos/DutchAuctionBidEvent
   backend/dtos/HashToProject
   backend/dtos/Project
   backend/dtos/ProjectEvaluationEvent
   backend/dtos/ProjectRegisterEvent
   backend/dtos/ProjectTemplate
   backend/dtos/TokenCreationEvent
   backend/dtos/User
   backend/dtos/VoteDelegateEvent
   backend/dtos/VoteEvent
   backend/dtos/WhitelistInsertEvent
   backend/dtos/WhitelistRemoveEvent

.. toctree::
   :maxdepth: 1
   :caption: Frontend

   frontend/Home New
   frontend/Project List

   frontend/Create Tokens
   frontend/Create Auction
   frontend/Auctions
   frontend/Project
   frontend/Auction
   frontend/Profile Page

   frontend/Not Authorized
   frontend/Viewer
   frontend/Admin
   frontend/About
   frontend/User Not Verified
   frontend/User Verified
   frontend/Apply 
   frontend/How To Use

