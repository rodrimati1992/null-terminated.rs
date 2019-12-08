extern crate null_terminated;
use null_terminated::{Nul,nul_of_ref};

static UNSOUND: &Nul<&std::convert::Infallible> = nul_of_ref![&0];

fn main(){
    dbg!(UNSOUND[0]);
}

