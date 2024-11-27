# social_media_app
Live demo: https://tdsocialmediaapp.netlify.app/

<img width="1398" alt="Screen Shot 2022-02-17 at 8 54 41 PM" src="https://user-images.githubusercontent.com/34137087/154602709-694ede3d-8151-41ca-9b54-2a0da926a2e5.png">


- Install [Node](https://nodejs.org/en/download/)
- Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Clone the repository `git clone https://github.com/tddag/social_media_app`
- Install server dependencies `cd backend && npm install`
- Install client dependencies `cd frontend && npm install`
- Setup [Sanity](https://www.sanity.io/)
- Setup [Google OAuth Client](https://console.cloud.google.com/auth/clients/)
- Setup client environment variables (./frontend/.env):
    <table>
        <tr>
            <th>Variable</th>
            <th>Value</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>REACT_APP_GOOGLE_OAUTH_CLIENT_ID</td>
            <td>630587915727-s0.........apps.googleusercontent.com</td>
            <td>Google API Token</td>
        </tr>   
        <tr>
            <td>REACT_APP_SANITY_PROJECT_ID</td>
            <td>p223q..</td>
            <td>Sanity Project ID</td>
        </tr>   
        <tr>
            <td>REACT_APP_SANITY_TOKEN</td>
            <td>skt4tiizJKLpd....</td>
            <td>Sanity Token</td>
        </tr>            
                                              
    </table>
- Start the server: `cd backend && npm run start`
- Start the client: `cd frontend && npm run start`


# Functionalities
- Google Authentication
    <table>
        <tr>
            <td><img src="./screenshots/google_authentication.png" alt="google_authentication"></td>
        </tr>
    </table>
- Pin Listing, Filter by Catagory
    <table>
        <tr>
            <td><img src="./screenshots/pin_listing_1.png" alt="pin_listing_1"></td>
            <td><img src="./screenshots/pin_listing_2.png" alt="pin_listing_2"></td>            
        </tr>
    </table>
- Pin Details, Post a Comment
    <table>
        <tr>
            <td><img src="./screenshots/pin_details.png" alt="pin_details"></td>
        </tr>
    </table>
- Dowload Pin, Save Pin, Open Source Link
    <table>
        <tr>
            <td><img src="./screenshots/pin_options.png" alt="pin_options"></td>
        </tr>
    </table>

# Technologies/Libraries
- Sanity: headless CMS (Content Management System)
- React: Web library
- Styled Components: CSS styling
- TailwindCSS: CSS framework
- postcss: Transforming styles with JS plugins
