import { Component } from '@angular/core';
import { VERSION, Routes, RouterModule } from '@angular/router';

const routes: Routes = [];

@Component({
    imports: [VERSION.forRoot(routes)],
    exports: [RouterModule]
});
export class AppRoutingModule { }