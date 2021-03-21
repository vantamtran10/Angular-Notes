# Angular-Notes
1. error: Property ‘X’ has no initializer and is not definitely assigned in the constructor..
> > > W: When we passing data from parent Component to Child Component
> > > Fix: Adding @Input() X?: string; // This is a typescript error, just make X is optional.
