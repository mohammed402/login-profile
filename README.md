# login-profile
#facebook login profile with angular material
ng add @angular/material
import {
  MatIconModule,
  MatButtonModule,
  MatCardModule } from '@angular/material';
imports: [
  MatIconModule,
  MatButtonModule,
  MatCardModule
],
import { AuthService, FacebookLoginProvider, SocialUser } from 'angularx-social-login';
export class AppComponent implements OnInit {
}
user: SocialUser;
loggedIn: boolean;
constructor(private authService: AuthService) { }
