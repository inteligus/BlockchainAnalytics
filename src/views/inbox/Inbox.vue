<template>
   <div id="inbox">
      <div class="inbox-wrapper">
         <div class="row no-gutters">
            <div class="col-sm-4 col-md-4 col-lg-4 col-xl-2 b-100">
               <div class="inner-tab">
                  <ul class="list-group mb-30">
                     <li class="list-group-item active ripple">
                        <a class="d-flex justify-content-between w-100">
                           <span><i class="ti-archive fa-inverse mr-20" aria-hidden="true"></i> Index</span>
                           <span class="badge badge-danger">20</span>
                        </a>
                     </li>
                     <li class="list-group-item ripple">
                        <a>
                           <span><i class="ti-location-arrow mr-20" aria-hidden="true"></i> Sent</span>
                        </a>
                     </li>
                     <li class="list-group-item ripple">
                        <a>
                           <span><i class="ti-email mr-20" aria-hidden="true"></i> Draft</span>
                        </a>
                     </li>
                     <li class="list-group-item ripple">
                        <a>
                           <span><i class="ti-trash mr-20" aria-hidden="true"></i> Trash</span>
                        </a>
                     </li>
                  </ul>
                  <div class="labels">
                     <ul class="list-unstyled">
                        <li>
                           <span><i class="ti-clip mr-20" aria-hidden="true"></i>Labels</span>
                        </li>
                        <li>
                           <span class="square-10 badge badge-success mr-20"></span>
                           <span>Corporate</span>
                        </li>
                        <li>
                           <span class="square-10 badge badge-warning mr-20"></span>
                           <span>Personal</span>
                        </li>
                        <li>
                           <span class="square-10 badge badge-primary mr-20"></span>
                           <span>Statements</span>
                        </li>
                        <li>
                           <span class="square-10 badge badge-danger mr-20"></span>
                           <span>Projects</span>
                        </li>
                     </ul>
                  </div><!-- labels closed -->
               </div><!-- inner tab closed -->
            </div>
            <div class="col-sm-8 col-md-8 col-lg-8 col-xl-4 b-100">
               <div class="inner-tab">
                  <ul class="list-group list-unstyled">
                     <li class="list-group-item d-flex justify-content-between">
                        <div class="d-flex align-content-start">
                           <h3 class="text-capitalize">Inbox</h3>
                        </div>
                        <div class="d-flex align-content-end">
                           <a><i class="fa fa-refresh fa-spin" aria-hidden="true"></i></a>
                        </div>
                     </li>
                     <li class="list-group-item">
                        <div class="search-list w-100">
                           <div class="input-group">
                              <input type="text" class="form-control" placeholder="Search for...">
                              <span class="input-group-btn">
                                 <button class="btn btn-primary" type="button"><i class="fa fa-search" aria-hidden="true"></i></button>
                              </span>
                           </div>
                        </div>
                     </li>
                  </ul>
                  <div class="idb-inbox-sidebar">
                     <ul class="nav nav-tabs" role="tablist">
                        <li class="nav-item">
                           <a class="nav-link active ripple" data-toggle="tab" href="#tab-1" role="tab">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-1.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-10 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">John Brett</h5>
                                       <span class="pull-right small">1:25</span>
                                    </div>
                                    <p class="text-primary mb-10">Create new profile request</p>
                                    <p class="text-muted mb-0">When the equation, first to ability the forwards, the a but travelling</p>
                                 </div>
                              </div>
                           </a>
                        </li>
                        <li class="nav-item">
                           <a class="nav-link ripple" data-toggle="tab" href="#tab-2" role="tab">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-2.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-danger square-10 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Vecky Brett</h5>
                                       <span class="pull-right small">1:25</span>
                                    </div>
                                    <p class="text-primary mb-10">Create new profile request</p>
                                    <p class="text-muted mb-0">When the equation, first to ability the forwards, the a but travelling</p>
                                 </div>
                              </div>
                           </a>
                        </li>
                        <li class="nav-item">
                           <a class="nav-link ripple" data-toggle="tab" href="#tab-3" role="tab">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-3.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-10 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Ray Gold</h5>
                                       <span class="pull-right small">1:25</span>
                                    </div>
                                    <p class="text-primary mb-10">Create new profile request</p>
                                    <p class="text-muted mb-0">When the equation, first to ability the forwards, the a but travelling</p>
                                 </div>
                              </div>
                           </a>
                        </li>
                        <li class="nav-item">
                           <a class="nav-link ripple" data-toggle="tab" href="#tab-4" role="tab">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-4.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-10 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Hugh Nion</h5>
                                       <span class="pull-right small">1:25</span>
                                    </div>
                                    <p class="text-primary mb-10">Create new profile request</p>
                                    <p class="text-muted mb-0">When the equation, first to ability the forwards, the a but travelling</p>
                                 </div>
                              </div>
                           </a>
                        </li>
                        <li class="nav-item">
                           <a class="nav-link ripple" data-toggle="tab" href="#tab-5" role="tab">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-5.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-warning square-10 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Monen Duke</h5>
                                       <span class="pull-right small">1:25</span>
                                    </div>
                                    <p class="text-primary mb-10">Create new profile request</p>
                                    <p class="text-muted mb-0">When the equation, first to ability the forwards, the a but travelling</p>
                                 </div>
                              </div>
                           </a>
                        </li>
                     </ul>
                  </div><!-- idb inbox sidebar closed -->
               </div><!-- inner tab closed -->
            </div>
            <div class="col-sm-12 col-md-12 col-lg-12 col-xl-6 b-100">
               <div class="idb-inbox-content">
                  <div class="idb-block">
                     <div class="idb-block-title">
                        <div class="d-flex justify-content-between">
                           <div class="d-flex align-content-start">
                              <h3 class="mb-0 text-capitalize">To:John Mayers</h3>
                           </div>
                           <div class="d-flex align-content-end">
                              <ul class="inbox-action list-inline mb-0">
                                 <li class="list-inline-item">
                                    <a><i class="fa fa-reply" aria-hidden="true"></i></a>
                                 </li>
                                 <li class="list-inline-item">
                                    <a><i class="fa fa-reply-all" aria-hidden="true"></i></a>
                                 </li>
                                 <li class="list-inline-item">
                                    <a><i class="fa fa-exclamation-triangle" aria-hidden="true"></i></a>
                                 </li>
                                 <li class="list-inline-item">
                                    <a><i class="fa fa-print" aria-hidden="true"></i></a>
                                 </li>
                                 <li class="list-inline-item">
                                    <a><i class="fa fa-trash" aria-hidden="true"></i></a>
                                 </li>
                              </ul>
                           </div>
                        </div>
                     </div>
                     <div class="idb-block-content">
                        <div class="tab-content">
                           <div class="tab-pane fade show active" id="tab-1" role="tabpanel">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-1.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-15 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column w-100">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Raymond Barrett</h5>
                                       <span class="pull-right small inbox-time">February 7th, 2018</span>
                                    </div>
                                    <p class="mb-10">Registration Question <span class="text-muted">&lt;bryan@solutions.com&gt;</span></p>
                                 </div>
                              </div>
                              <div class="dropdown-divider my-30"></div>
                              <div class="mb-40">
                                 <p class="mb-30">Hi Mike,</p>
                                 <p>When the equation, first to ability the forwards, the a but travelling, outlines sentinels bad expand to goodness. Behind if have at the even I and how work, completely deference who boss actually designer; Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                                 <p>Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                              </div>
                              <p>Regards,</p>
                              <p>Mike Mayers</p>
                              <div class="dropdown-divider my-40"></div>
                              <div class="attachments">
                                 <p><i class="fa fa-paperclip" aria-hidden="true"></i> 2 Attachments</p>
                                 <ul class="list-inline">
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-6.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                 </ul>
                              </div>
                           </div>
                           <div class="tab-pane fade" id="tab-2" role="tabpanel">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-2.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-15 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column w-100">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Raymond Barrett</h5>
                                       <span class="pull-right small inbox-time">February 7th, 2018</span>
                                    </div>
                                    <p class="mb-1">Registration Question <span class="text-muted">&lt; bryan@solutions.com &gt;</span></p>
                                 </div>
                              </div>
                              <div class="dropdown-divider my-30"></div>
                              <div class="mb-40">
                                 <p class="mb-30">Hi Lisa,</p>
                                 <p>When the equation, first to ability the forwards, the a but travelling, outlines sentinels bad expand to goodness. Behind if have at the even I and how work, completely deference who boss actually designer; Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                                 <p>Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                              </div>
                              <p>Regards,</p>
                              <p>Lisa Mayers</p>
                              <div class="dropdown-divider my-40"></div>
                              <div class="attachments">
                                 <p><i class="fa fa-paperclip" aria-hidden="true"></i> 2 Attachments</p>
                                 <ul class="list-inline">
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                 </ul>
                              </div>
                           </div>
                           <div class="tab-pane fade" id="tab-3" role="tabpanel">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-3.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-15 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column w-100">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Raymond Barrett</h5>
                                       <span class="pull-right small inbox-time">February 7th, 2018</span>
                                    </div>
                                    <p class="mb-10">Registration Question <span class="text-muted">&lt; bryan@solutions.com &gt;</span></p>
                                 </div>
                              </div>
                              <div class="dropdown-divider my-30"></div>
                              <div class="mb-40">
                                 <p class="mb-30">Hi Juliya,</p>
                                 <p>When the equation, first to ability the forwards, the a but travelling, outlines sentinels bad expand to goodness. Behind if have at the even I and how work, completely deference who boss actually designer; Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                                 <p>Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                              </div>
                              <p>Regards,</p>
                              <p>Juliya Mayers</p>
                              <div class="dropdown-divider my-40"></div>
                              <div class="attachments">
                                 <p><i class="fa fa-paperclip" aria-hidden="true"></i> 2 Attachments</p>
                                 <ul class="list-inline">
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                 </ul>
                              </div>
                           </div>
                           <div class="tab-pane fade" id="tab-4" role="tabpanel">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-4.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-15 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column w-100">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Raymond Barrett</h5>
                                       <span class="pull-right small inbox-time">February 7th, 2018</span>
                                    </div>
                                    <p class="mb-10">Registration Question <span class="text-muted small">&lt; bryan@solutions.com &gt;</span></p>
                                 </div>
                              </div>
                              <div class="dropdown-divider my-30"></div>
                              <div class="mb-40">
                                 <p class="mb-30">Hi Rosa,</p>
                                 <p>When the equation, first to ability the forwards, the a but travelling, outlines sentinels bad expand to goodness. Behind if have at the even I and how work, completely deference who boss actually designer; Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                                 <p>Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                              </div>
                              <p>Regards,</p>
                              <p>Rosa Mayers</p>
                              <div class="dropdown-divider my-40"></div>
                              <div class="attachments">
                                 <p><i class="fa fa-paperclip" aria-hidden="true"></i> 2 Attachments</p>
                                 <ul class="list-inline">
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                 </ul>
                              </div>
                           </div>
                           <div class="tab-pane fade" id="tab-5" role="tabpanel">
                              <div class="d-flex justify-content-start">
                                 <div class="d-flex align-items-start flex-column mr-30 pos-relative">
                                    <img src="/static/img/user-5.jpg" class="rounded-circle" width="65" height="65" alt="user thumb" />
                                    <span class="badge badge-success square-15 top-right-badge fa-notify"></span>
                                 </div>
                                 <div class="d-flex align-items-start flex-column w-100">
                                    <div class="clearfix w-100">
                                       <h5 class="pull-left">Raymond Barrett</h5>
                                       <span class="pull-right small inbox-time">February 7th, 2018</span>
                                    </div>
                                    <p class="mb-1">Registration Question <span class="text-muted">&lt; bryan@solutions.com &gt;</span></p>
                                 </div>
                              </div>
                              <div class="dropdown-divider my-30"></div>
                              <div class="mb-40">
                                 <p class="mb-30">Hi Rosa,</p>
                                 <p>When the equation, first to ability the forwards, the a but travelling, outlines sentinels bad expand to goodness. Behind if have at the even I and how work, completely deference who boss actually designer; Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                                 <p>Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.Monstrous with geared from far and these, morals, phase rome; Class. Called get amidst of next.</p>
                              </div>
                              <p>Regards,</p>
                              <p>Rosa Mayers</p>
                              <div class="dropdown-divider my-40"></div>
                              <div class="attachments">
                                 <p><i class="fa fa-paperclip" aria-hidden="true"></i> 2 Attachments</p>
                                 <ul class="list-inline">
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/post-3.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                    <li class="list-inline-item">
                                       <div class="overlay-wrap">
                                          <img src="/static/img/pic-1.jpg" alt="attachments" class="img-fluid img-thumbnail" width="180" height="180"/>
                                          <div class="card-img-overlay primary-tp-layer pos-center text-center">
                                             <div class="center-holder">
                                                <ul class="list-inline">
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-eye fa-inverse"></i></a>
                                                   </li>
                                                   <li class="list-inline-item">
                                                      <a href="javascript:void(0)" class="mx-10 mb-10"><i class="fa fa-download fa-inverse"></i></a>
                                                   </li>
                                                </ul>
                                             </div>
                                          </div>
                                       </div>
                                    </li>
                                 </ul>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div><!-- idb block Closed -->
               </div><!-- idb inbox content closed -->
            </div>
         </div><!-- row closed -->
      </div><!-- inbox Wrapper closed -->
   </div>
</template>
